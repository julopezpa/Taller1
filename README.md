# Taller1
# GRUPO:Byte Builders
![image](https://user-images.githubusercontent.com/124606636/225486236-e4618eec-16f2-465f-b317-142d70c5942e.png)

# Ejercicios taller
# (1)Realice el quiz Python Beginner Quiz (20 preguntas) y adjunte pantallazo con el resultado (mínimo 90% bien).
Quiz de:Alejandro ortega 

![image](https://user-images.githubusercontent.com/124606636/225486402-c70aa242-aec0-48d4-b66a-3ddb7115d62b.png)

Quiz de:Julian López

![image](https://user-images.githubusercontent.com/124606636/225486460-186fed94-f8db-4266-948a-831f25c8911f.png)

Quiz de:Carlos Villamil

![image](https://user-images.githubusercontent.com/124606636/225487914-e45983fa-6fb8-4ad8-b019-2709d9f97009.png)


# (2)Realice un programa que lea tres números reales y determine cuál es el mayor.
    a=float(input("ingrese una numero real"))
    b=float(input("ingrese una numero real"))
    c=float(input("ingrese una numero real"))
    if a>b:
        if a>c:
            print("el numero mayor es "+str(a))
        else:
            print("el numero mayor es "+str(c))
    elif b>c:
        print("el numero mayor es "+str(b))
    else:
        print("el numero mayore es "+str(c))
# Explicacion
EL programa funciona ingresando 3 variables flotantes, las cuales despues se comparan sucesivamente usando if , elif y else, para asi poder saber cual de todas las variables corresponde al numero mayor
# (3)Realice un programa que lea un número enteros y determine si es par o impar.
    n = int(input("Ingrese un número: ")) 
    if n==0:
        print(n, "es neutro")
    elif n % 2 == 0: print(n, "es par")
    else:
        print(n, " es impar")
# Explicacion
Se ingresa una variable entera la cual ,se compara primero con 0 para saber si no es un numero neutro, despues se mira el residuo de la divicion dela variable con 2, y si este es igual a 0 significa que es par , pero si no ,que es un numero impar

![image](https://user-images.githubusercontent.com/124606636/225490249-ff09842d-be30-4637-af51-940b6b03d687.png)

# (4)Realice un programa que lea dos números reales y determine si el primero es múltiplo del segundo.
    a= float(input("Ingresa el primer número: "))
    b= float(input("Ingresa el segundo número: "))

    if a % b == 0:
        print(a, "es múltiplo de", b)
    else:
        print(a, "no es múltiplo de", b)
# Explicacion
Se ingresan dos variables flotantes las cuales se van a divir entre si (la primera sobre la segunda) y despendiendo de su residuo, se concluira si la primera variable es multiplo de la segunda

# (5)Realice un programa que lea tres números reales y determine si la suma de los dos primeros es mayor, menor o igual que el tercer número.
    a= float(input("Ingrese el primer numero: "))
    b= float(input("Ingrese el segundo numero: "))
    c= float(input("Ingrese el tercer numero: "))
    if a+b>c:
        print("La suma de "+str(a)+" y "+str(b)+" es mayor que "+str(c))
    elif a+b<c:
        print("La suma de "+str(a)+" y "+str(b)+" es menor que "+str(c))
    else a+b==c:
            print("La suma de "+str(a)+" y "+str(b)+" es igual que "+str(c))
# Explicacion
Se ingresan 3 variables flotantes las cuales se suman las dos primeras, para despues ser comparadas con la tercera(>,<,=), asi permitiendonos saber si las suma de las dos primeras es un valor igual, mayor, o menor que el valor de la ultima variable 

![image](https://user-images.githubusercontent.com/124606636/225491621-199d0fbb-c496-42bc-b53a-a42c460149d6.png)

# (6)Escriba un programa que solicite al usuario una letra y determine si es una vocal o una consonante.
    aa=input("Ingrese una letra")
    if aa in "a,e,i,o,u,A,E,I,O,U,á,é,í,ó,ú":
        print(str(aa)+" es una vocal")
    elif aa in "b,c,d,f,g,h,j,k,l,m,n,ñ,p,q,r,s,t,v,w,x,y,z,B,C,D,F,G,H,J,K,L,M,N,Ñ,P,Q,R,S,T,V,W,X,Y,Z":
        print(str(aa)+" es una consonante")
    else:
        print(str(aa)+" no es una letra")
# Explicacion
Se ingresa un caracter al programa y se mria si esta dentro de las lista creadas, para asi despues imprimir lo correspondiente

# (7)Escriba un programa que pida 5 números reales y calcule las siguientes operaciones:
    n1= float(input("Ingrese un número: ")) 
    n2= float(input("Ingrese un número: ")) 
    n3= float(input("Ingrese un número: ")) 
    n4= float(input("Ingrese un número: ")) 
    n5= float(input("Ingrese un número: ")) 
    #promedio
    x=(n1+n2+n3+n4+n5)/5
    print ("el promedio es ",x)
    #mediana
    import statistics
    numeros=[n1,n2,n3,n4,n5]
    y=statistics.median(numeros)
    print("la mediana es",y)
    #promedio multiplicativo
    y=(n1*n2*n3*n4*n5)**(1/5)
    print("el promedio multiplicativo es",y)
    #numeros de forma ascendente
    p=sorted(numeros)
    print("los numeros ordenados de forma ascendente queda ",p)
    #numeros de forma descendente
    t=sorted(numeros,reverse=True)
    print("los numeros ordenados de forma descendente queda ",t)
    #numero mayor elevado el menor
    mayor = max(numeros)
    menor = min(numeros)
    potencia = mayor ** menor
    print("la potencia de ", mayor, " elevada ", menor," es de ", potencia)
    #la raiz cubica del numero menor
    raiz=menor**(1/3)
    print("la raiz cubica de ", menor," es ", raiz)
# Explicacion
Se ingresan 5 variables flotantes a las cuales se les quiere determinar el promedio: suma de las 5 variables que despues se divide en 5, la mediana: se usa una libreria que hace este proceso por si sola, el promedio multiplicativo: la multiplicacion de las 5 variables para despues sacarle la raiz quitan, de forma ascendete: se usa la funcion sorted para ordenar los numeros dentro de la lista llamada "numeros", forma descenten: se usa la funcion sorted para ordenar los numeros dentro de la lista llamada "numeros" pero haciendo que sea al contrario  con el reverse=True, numero mayor elevado el menor: se usa las funciones max y min para asi poder saber cuales son los valores mayores deons dentro de las lista"numeros" para despues elevar al menor en el mayor, la raiz cubica del menor: se eleva el numero menor a 1/3

# (8)Escriba un programa al que se le ingrese la frecuencia de una onda en hz y como salida arroje en que parte del espectro electromagnético se encuentra.
    x : float
    x = float(input(" Insertar la frecuencia deseada: ")) 

    if x < 3e9:
        print("La frecuencia " + str(x) + " esta ubicada en ondas de radio" )
    elif x < 3e12:
        print("La frecuencia " + str(x) + " esta ubicada en ondas de microondas" )
    elif x  < 4.3e14:
        print("La frecuencia " + str(x) + " esta ubicada en ondas de infrrarrojo" )
    elif x < 7.5e14:
        print("La frecuencia " + str(x) + " esta ubicada en ondas de luz visible" )

    elif x < 3e17:
        print("La frecuencia " + str(x) + " esta ubicada en ondas ultravioletas" )

    elif x < 3e19:
        print("La frecuencia " + str(x) + " esta ubicada en ondas de Rayos X" )

    else:
        print("La frecuencia " + str(x) + " esta ubicada en ondas de rayos gamma" )
# Explicacion
Se ingresa una variable flotante que se va comparando (>,<,=)con una serie de numeros para saber en que parte del espectro electromagnético se encuentra

# (9)Escriba un programa que reciba el nombre en minúsculas de un país de America y retorne la ciudad capital, si el país no pertenece al continente debe arrojar país no identificado.
     pais=input("Inserte el nombre del pais del que quiere conocer la capital; en minuscula")
    if pais in "canada":
        print("Otawwa")
    elif pais in "estados unidos":
        print("Washington DC")
    elif pais in "mexico":
        print("México DF")                                                                                  
    elif pais in "belice":
        print("Belmopán")
    elif pais in "costa rica":
        print("San José")
    elif pais in "el salvador":
        print("San Salvador")
    elif pais in "guatemala":
        print("Ciudad de Guatemala")
    elif pais in "honduras":
        print("Tegucigalpa")
    elif pais in "nicaragua":
        print("Managua")
    elif pais in "panama":
        print("Panamá")
    elif pais in "argentina":
        print("Buenos Aires")
    elif pais in "bolivia":
        print("Sucre")
    elif pais in "brazil":
        print("Brasilia")
    elif pais in "chile":
        print("Santiago de Chile")
    elif pais in "colombia":
        print("Bogotá")
    elif pais in "ecuador":
        print("Quito")
    elif pais in "paraguay":
        print("Asunción")
    elif pais in "peru":
        print("Lima")
    elif pais in "surinam":
        print("Parabarimo")
    elif pais in "trinidad y tobago":
        print("Puerto España")
    elif pais in "uruguay":
        print("Montevideo")
    elif pais in "venezuela":
        print("Caracas")
    elif pais in "antigua y barbuda":
        print("Saint John")
    elif pais in "bahamas":
        print("Nasáu")
    elif pais in "barbados":
        print("Bridgetown")
    elif pais in "cuba":
        print("La Habana")
    elif pais in "dominica":
        print("Roseau")
    elif pais in "granada":
        print("Saint George")
    elif pais in "guyana":
        print("Georgetown")
    elif pais in "haiti":
        print("Puerto Príncipe")
    elif pais in "jamica":
        print("Kingston")
    elif pais in "republica dominicana":
        print("Santo Domingo")
    elif pais in "san cristobal y nieves":
        print("Basseterre")
    elif pais in "san vicente y granadinas":
        print("Kingstown")
    elif pais in "santa lucia":
        print("Castries")
    else:
        print("No siguio los parametros")   
# Explicacion
Se ingresa una variable con una cadena de caracteres( nombre de un pais de america) y se va comparando usando if elif y else, si concuerda se imprime la capital del pais , sino significa que el pais no cumple con los parametros que se solicitaros

# (10)Escriba un programa que dada una distancia calcule el tiempo que se demoran distintas cosas en recorer una distancia en especifico
    distancia = float(input("Ingrese la distancia en metros: "))
    luz = distancia / 299792458
    sonido = distancia / 343
    vehiculo = distancia / (120 / 3.6)
    bolt = distancia / (44.72 / 3.6)
    print("Tiempo que le tomaría a la luz recorrer la distancia: "+ str(luz)+ " segundos")
    print("Tiempo que le tomaría al sonido (en el aire) recorrer la distancia: "+str(sonido)+ " segundos")
    print("Tiempo que le tomaría al vehículo comercial más veloz recorrer la distancia: "+str(vehiculo)+ " segundos")
    print("Tiempo que le tomaría a Bolt recorrer la distancia: "+ str(bolt)+" segundos")
# Explicacion
Se ingresa una variable flotante, y otras 4 que son valores que dependen de la variable ingresada/ un valor en especifico, para asi imprimir lo que demoran en recorrer la luz, el sonido, un vehiculo, y Bold, una distancia en especifico( la variable)




