## Práctica con chroot


```bash
1. Importar una maquina Ubuntu y le meter el disco de Kali linux.
```
![lsblk](/Capturas/Captura2.png)

```bash
2. Iniciar e instalar Kali linux.
```
![lsblk](/Capturas/Captura3.png)


```bash
3. Mirar el estado de ssh.
```
![lsblk](/Capturas/Captura4.png)


```bash
4. Conectarse por SSH desde PowerShell  a Kali.
```
![lsblk](/Capturas/Captura4.png)

![lsblk](/Capturas/Captura5.png)

```bash
5. Mirar los archivos y particiones de Kali.
```
![lsblk](/Capturas/Captura6.png)
![lsblk](/Capturas/Captura7.png)
![lsblk](/Capturas/Captura8.png)
![lsblk](/Capturas/Captura9.png)


```bash
6. Crear la carpeta /mnt/recuperar y  montarla en el disco SDA3.
```
![lsblk](/Capturas/Captura10.png)
![lsblk](/Capturas/Captura11.png)

```bash
7. Mirar que la información de SDA3  contiene nuestra información de Ubuntu esta en /mnt/recuperar.
```
![lsblk](/Capturas/Captura12.png)


```bash
8. Montar /dev en nuestra carpeta de /mnt/recuperar/dev.
```


```bash
9. Montar /proc en nuestra carpeta de /mnt/recuperar/proc.
```


```bash
10. Montar /sys en nuestra carpeta de /mnt/recuperar/sys.
```
![lsblk](/Capturas/Captura13.png)
```bash
11. Hacer chroot para posicionarme donde quiero que este el directorio raíz.
```
![lsblk](/Capturas/Captura14.png)
```bash
12. Mirar el usuario de Ubuntu y comprar que este en Kali, con esto somos root en Ubuntu y cambiamos la contraseña con passwd  usuario.
```
![lsblk](/Capturas/Captura15.png)
```bash
13. Por último, apagar la máquina,eliminamos el disco y comprobamos que se le ha cambiado la contraseña al usuario de Ubuntu y que podemos entrar.
```
![lsblk](/Capturas/Captura16.png)
![lsblk](/Capturas/Captura17.png)
