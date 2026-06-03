Adelia Vivian Conscetta 3A




FurColor.java
criado seguindo o padrão em habitat e trainingLevel
cada cor possui código numerico e nome de exibicao
implementados os metodos getCode(), getDisplayName() e fromCode()

Cat.java
criada como subclasse de Animal
implementados todos os atributos
o construtor define:
  lives = 7
  Habitat.DOMESTIC quando isIndoor = true
  Habitat.WILD_FOREST quando isIndoor = false
  isWild = !isIndoor

metodos sobrescritos
makeSound()
sleep()
displayInfo()

sobrecarga (overload)
move(int distance, int speed)
move(int distance, String target)

metodos adicionais
purr()
loseLife()


