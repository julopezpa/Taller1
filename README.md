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
Se ingresan dos variables las cuales se van a divir entre si (la primera sobre la segunda) y despendiendo de su residuo, se concluira si la primera variable es multiplo de la segunda
