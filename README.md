# Permantente-2C
Ventana para logearse
Se implementa la galería "tkinter" para obtener una ventana gráfica
Primero implementamos una ventana donde nos ponga un mensaje de bienvenida 
y abajo un botón de logearse
definimos sus medidas
![image](https://user-images.githubusercontent.com/101744240/176833421-414e2f27-f30a-4f92-b03d-2c79ff8cbe65.png)
luego definimos una ventana emergente donde pedirá que ingreses tu Usuario y tu contraseña
Usuario: ucsp
Contraseña: 123 
![image](https://user-images.githubusercontent.com/101744240/176833646-8051cbd2-26de-4eec-b0e9-2c2c7cc044ea.png)
en caso de que no ingreses valores validos te saldrá un mensaje de advertencia
**if len(usuario) == 0:
            messagebox.showwarning('Mensaje', 'El campo Usuario es obligatorio.')
            return**
![image](https://user-images.githubusercontent.com/101744240/176833728-6cd140b6-b653-4310-a87b-e23935d23035.png)
Pero al ingresar valores validos te habrás logeado con exito
if usuario == 'ucsp' and clave == '123':
            messagebox.showinfo('Mensaje', 'Ha iniciado sesión de forma satisfactoria.')

![image](https://user-images.githubusercontent.com/101744240/176833900-605b0a58-eae6-42d3-b68b-9510bf1916c2.png)
