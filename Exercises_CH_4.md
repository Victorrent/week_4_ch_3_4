1.
>> def string_shuffle(s)
>>   s.split('').shuffle.join
>> end
>> string_shuffle("foobar")
=> "oobfra"
2.
>> class String
>>   def shuffle
>>     self.split('').shuffle.join
>>   end
>> end
>> "foobar".shuffle
=> "borafo"
3.
person1 = {first: "Jon", last: "Smith"}
person2 = {:first => "Diane", :last => "Smith"}
person3 = {}
person3[:first] = "Selfie"
person3[:last] = "Smith"
params = {:father => person1, child: person3}
params[:mother] = person2
4.
{"a" => 100, "b" =>300}