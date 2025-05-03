# My first main header

## Some secondary header


###### I have never used header of level 6, the smallest one, before.

~~~ruby
# Can Yaktocat code in Ruby?

class Cat
  attr_reader :name, :programming_skills

  def initialize(name, programming_skills: [])
    @name = name
    @programming_skills = programming_skills
  end

  def can_code_in_ruby?
    programming_skills.include?(:ruby)
  end
end

yaktocat = Cat.new("Yaktocat", programming_skills: [:ruby])
yaktocat.can_code_in_ruby?
~~~

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)
