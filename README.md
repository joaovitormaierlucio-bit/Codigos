while 10>0:
    print("1 - adição")
    print("2 - subtração")
    print("3 - multiplicação")
    print("4 - divisão")
    print("5 - elevado")
    print("6 - porcentagem")
    print("7 - raiz")
    escolha=input("escolha uma opção")
    if escolha == "1":
       h=int(input("qualquer numero"))
       i=int(input("2 qualquer numero"))
       print(h+i)
       input()
    if escolha == "2":
       j=int(input("qualquer numero"))
       k=int(input("2 qualquer numero"))
       print(j-k)
       input()
    if escolha == "3":
       l=int(input("qualquer numero"))
       m=int(input("2 qualquer numero"))
       print(l*m)
       input()
    if escolha == "4":
       n=int(input("qualquer numero"))
       o=int(input("2 qualquer numero"))
       print(n/o)
       input()
    if escolha == "5":
       p=int(input("qualquer numero"))
       q=int(input("2 qualquer numero"))
       print(p**q)
       input()
    if escolha == "6":
       valor = float(input("Digite o valor: "))
       porcentagem = float(input("Digite a porcentagem: "))
       resultado = (valor * porcentagem) / 100
       print(resultado)
       input()
    if escolha == "7":
       u=float(input("Digite o número: "))
       v=u ** 0.5
       print(v)
       input()
       
