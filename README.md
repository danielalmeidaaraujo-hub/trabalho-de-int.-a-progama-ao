# trabalho-de-int.-a-progama-ao

class pessoa:


   def __init__(self, nome, idade):
       self.nome = nome
       self.idade = idade


pessoa = pessoa("mariana", 6)
print(f"{pessoa.nome} / {pessoa.idade}")


=-=-=-=-=-=-=-=-=-=-=-=--=-=-==-=-=-=-=-=

class Produto:


   def __init__(self, nome, preço, estoque):
       self.nome = nome
       self.preço = preço
       self.estoque = estoque


Produto1 = Produto("detergente", 3.45, 300)
Produto2 = Produto("sabão em pó", 7.59, 300)
print(f"{Produto1.nome} , {Produto1.preço} , {Produto1.estoque}")
print(f"{Produto2.nome} , {Produto2.preço} , {Produto2.estoque}")


=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=

class Produto:


   def __init__(self, nome, preço, estoque):
       self.nome = nome
       self.preço = preço
       self.estoque = estoque


Produto1 = Produto("detergente", 3.45, 300)
Produto2 = Produto("sabão em pó", 7.59, 300)
print(f"{Produto1.nome} , {Produto1.preço} , {Produto1.estoque}")
print(f"{Produto2.nome} , {Produto2.preço} , {Produto2.estoque}")

=-=-=-=-=-=-=-=-=-=-=-=--=-=-=-=-=-=-=--=--=-=-=--=-=

class Aluno:
   
    def __init__(self, nome, nota):
        self.nome = nome
        self.nota = nota


       
    def aprovado(self):
        if aluno.nota >= 6.0:
            return True
        else:
            return False


aluno = Aluno("sophya eloa", 7.7)
print(f"A {aluno.nome} tem {aluno.nota} de nota portanto {aluno.aprovado()}")


=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=

class Retangulo:


    def __init__(self, largura, altura):
        self.largura = largura
        self.altura = altura


    def CalcularPerimetro(self):
        perimetro = 2 * (self.largura + self.altura)
        return perimetro


meu_retangulo = Retangulo(8,8)


resultado = meu_retangulo.CalcularPerimetro()


print(f"o retangulo {meu_retangulo.altura + meu_retangulo.altura } tem um perimetreo de: {resultado}")


=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=

class ContaBancaria:
   
   def __init__(self):
       self.__saldo = 0.0


   def depositar(self, valor):
       if valor > 0:
           self.__saldo += valor
           print(f"Depósito de R$ {valor:.2f} realizado com sucesso.")
       else:
           print("Erro: O valor do depósito deve ser maior que zero.")


   def consultar_saldo(self):
       return self.__saldo

