# lista-lista = []

def adicionar():
    nome = input('digite um nome por vez:')
    lista.append(nome)
print()
def retirar_nome_da_lista():
    x=input('nome a ser retirado:')
    lista.remove(x)
def listar():
    print(lista)
opcao=1
while opcao!=4:
    print ("-----------------------------------------------")
    print ("MENU")
    print ("1 - adicionar")
    print ("2 - retirar nome da lista")
    print ("3 - lista")
    print("4 - sair")
    opcao=input('escolha uma opçao:')
    print("-----------------------------------------------")
    if opcao=="1":
        adicionar()
    elif opcao=="2":
        retirar_nome_da_lista()
    elif opcao=="3":
        listar()
    else:
        print("Opção Inválida!")
