# ROMAN-DE-LA-CRUZ.-FUNCIONES-3-W
prueba de envio de codigo y de screenshot

#Practicando funciones
2- Para llamar a una funcion, use la funcion nombrada y seguida de parentesis:
![image](https://github.com/user-attachments/assets/d41f6509-8205-4cd8-b588-0a4a29545fcc)
![image](https://github.com/user-attachments/assets/0e725149-748a-45b4-95c2-559afbcd225a)

3- El siguiente ejemplo tiene una función con un argumento (fname). Cuando se llama a la función, pasamos un nombre, que se usa dentro de la función para imprimir el nombre completo:
![image](https://github.com/user-attachments/assets/743e16bb-e3c9-4482-bf23-c3a19ee3fac9)
![image](https://github.com/user-attachments/assets/84252789-808c-4aa7-a796-74f83764ef89)


4- De forma predeterminada, se debe llamar a una función con la cantidad correcta de argumentos. Lo que significa que si su función espera 2 argumentos, debe llamar a la función con 2 argumentos, ni más ni menos.
![image](https://github.com/user-attachments/assets/a97bbc7e-8ca6-4de2-a64f-f5c90b01bbf7)
![image](https://github.com/user-attachments/assets/daedc644-d673-4044-80eb-3e42b3a9b57c)


5- Esta función espera 2 argumentos, pero solo obtiene 1:
![image](https://github.com/user-attachments/assets/851bc52b-53c6-480a-b540-214aecec82a5)
![image](https://github.com/user-attachments/assets/79d6b9f4-49fe-4013-a723-dbbeb1e091b1)

6- Si no sabe cuántos argumentos se pasarán a su función, agregue un * antes del nombre del parámetro en la definición de la función.
De esta manera, la función recibirá una tupla de argumentos y podrá acceder a los elementos en consecuencia:
Si se desconoce el número de argumentos, agregue un * antes del nombre del parámetro:
![image](https://github.com/user-attachments/assets/529ef25f-52e6-4d25-a367-8ac9cd62d9a9)
![image](https://github.com/user-attachments/assets/52be8643-1da3-40f6-ae00-476e48280f62)



7- También puede enviar argumentos con la sintaxis clave = valor.
![image](https://github.com/user-attachments/assets/7a7d16b9-65c9-4bb2-bd29-48281aa5b8f3)
![image](https://github.com/user-attachments/assets/68c79f44-a5ac-4a73-8bc4-1a6300474372)


8- Argumentos arbitrarios de palabras clave, **kwargs
Si no sabe cuántos argumentos de palabras clave se pasarán a su función, agregue dos asteriscos: ** antes del nombre del parámetro en la definición de la función.
De esta manera, la función recibirá un diccionario de argumentos y podrá acceder a los elementos en consecuencia:
Si se desconoce el número de argumentos de palabras clave, agregue un doble ** antes del nombre del parámetro:
![image](https://github.com/user-attachments/assets/3f5e363b-9532-487e-88c9-e7addab087e5)
![image](https://github.com/user-attachments/assets/8d3ae712-b811-4ead-934f-b6020490c622)

9- Valor de parámetro predeterminado
El siguiente ejemplo muestra cómo utilizar un valor de parámetro predeterminado.

Si llamamos a la función sin argumento, usa el valor predeterminado:
![image](https://github.com/user-attachments/assets/af587b81-80c3-49f5-8bfc-20e1853455c5)
![image](https://github.com/user-attachments/assets/ff04dc17-86b1-46a2-88ab-109a426013bb)

10- Pasar una lista como argumento
Puede enviar cualquier tipo de argumento de datos a una función (cadena, número, lista, diccionario, etc.) y será tratado como el mismo tipo de datos dentro de la función.
![image](https://github.com/user-attachments/assets/b7d4546f-168d-473c-97ad-45cc6c3ee3e7)
![image](https://github.com/user-attachments/assets/6282e159-e694-4056-81a5-bd79a56a57b6)

11- Regresa Valores
Para permitir que una función devuelva un valor, utilice la declaración de retorno:
![image](https://github.com/user-attachments/assets/57b5b6aa-8b85-47fb-a3b7-456e6a6a72f2)
![image](https://github.com/user-attachments/assets/a466d581-503c-4ae5-8698-a646b411b72c)

12- La declaración del pass
Las definiciones de función no pueden estar vacías, pero si por alguna razón tiene una definición de función sin contenido, ingrese la instrucción pass para evitar recibir un error.
![image](https://github.com/user-attachments/assets/178bcac5-b6b0-4f02-a132-f9f32a124782)
![image](https://github.com/user-attachments/assets/6a799159-857e-4e4f-aad1-6c09597a4dcf)

13- Argumentos sólo posicionales 
Puede especificar que una función pueda tener SÓLO argumentos posicionales o SÓLO argumentos de palabras clave.

Para especificar que una función solo puede tener argumentos posicionales, agregue , / después de los argumentos:

Ícono de validado por la comunidad
![image](https://github.com/user-attachments/assets/f288e99b-a638-43bb-879f-6eeb2640d515)
![image](https://github.com/user-attachments/assets/bceef59a-0363-4859-ba8a-2247da121eb9)

14
Sin , / en realidad se le permite usar argumentos de palabras clave incluso si la función espera argumentos posicionales
![image](https://github.com/user-attachments/assets/72290ef3-9941-43bb-a2df-04d57f34fe54)
![image](https://github.com/user-attachments/assets/938cb493-e26e-477e-9464-c28416f11778)


15
Pero al agregar , / obtendrá un error si intenta enviar un argumento de palabra clave:
![image](https://github.com/user-attachments/assets/1262bc06-3a6a-4383-b3c6-7354ba795946)
![image](https://github.com/user-attachments/assets/ce49b0a0-5cf2-4bfd-9ccd-61702a46bc30)


16
Argumentos de solo palabras clave
Para especificar que una función solo puede tener argumentos de palabras clave, agregue *, antes de los argumentos
![image](https://github.com/user-attachments/assets/52fb0271-6cc3-45d7-aa3d-caba596ae658)
![image](https://github.com/user-attachments/assets/e5df2fea-2abd-4bd3-afc6-d66ae65e1305)



17
Sin el *, se le permite utilizar argumentos posicionales incluso si la función espera argumentos de palabras clave:

![image](https://github.com/user-attachments/assets/648a8e24-7e12-41d0-8c61-739528133c72)
![image](https://github.com/user-attachments/assets/3618062c-cb4d-4e8f-a1b1-9bdfbc75303d)


18
Pero al agregar *, / obtendrás un error si intentas enviar un argumento posicional:

![image](https://github.com/user-attachments/assets/25ad55fd-59b7-40fd-b661-b40ba784170e)

![image](https://github.com/user-attachments/assets/e58314c5-66ad-4656-8739-561e1785dabc)

19
Combine solo posicional y solo palabras clave
Puede combinar los dos tipos de argumentos en la misma función.

Cualquier argumento antes de / es solo posicional y cualquier argumento después de * es solo de palabra clave.
![image](https://github.com/user-attachments/assets/88545db9-89ff-4ebe-9b95-0ba55fe5b258)
![image](https://github.com/user-attachments/assets/3d0cc2fb-e0e3-45aa-ad69-d3b5bf6cbadd)

20
![image](https://github.com/user-attachments/assets/308922db-2fa2-454a-86b3-00d94eb7ebd3)
![image](https://github.com/user-attachments/assets/e7f43b2f-ca25-433a-9615-46f77c25dc73)



