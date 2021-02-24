# CursoDeAdministracionDeServidoresLinux
# Clase#1
    Intrudicción
# Clase#2
    Distribuciones más utilizadas de Linux
        SO
            Ubuntu Server
            CentOS Server
        Usage statistics of operating systems for websites
            https://w3techs.com/technologies/overview/operating_system  
        Amazon
            https://thecloudmarket.com/stats
        linuxfoundation.org
            https://www.linuxfoundation.org/publications/2018/06/open-source-jobs-report-2018/
# Clase#3
    Instalación de Ubuntu Server
        Descarga e instalación de Virtual Box
        Descarga de ubuntu server
        Instalación de Ubuntu Sever con Virtual Box
# Clase#4
    Instrucciones para instalar CentOS
        Descarga e instalación de CentOS
# Clase#5
    Gestión del árbol de directorios
        Comandos
            Basicos (cd .., ls... etc)
# Clase#6
    Diferencias entre LESS, CAT, HEAD y TAIL para lectura de archivos
        Cat**
            Para archivos pequños.
        less**
        man name(space bajar, buscar "/"(n shift+N))
        tail
            tail -n 20 (últimas lineas del archivo)
            tail -f /var/log/auth.log /var/log/dpkg.log (se pueden concatenar varios logs al tiempo)
        head**
            head -n 12  (Primeras doce lineas)
# Clase#7
    Interacción con archivos y permisos
        chmod:
            chmod ugoa +rwx
                u => Usuario
                g => Grupo
                o => Otros
                a => all
            chmod u+x archivo.*
            chmod ugo +wrx
        chown:
            sudo chown user: file or dir
# Links:
    Canonical:
        https://ubuntu.com/advantage
    Linuxfoundation:
        https://www.linuxfoundation.org/resources/publications/open-source-jobs-report-2018
    Thecloudmarket(Amazon):
        https://thecloudmarket.com/stats
    Historical trends in the usage statistics of Linux subcategories for websites:
        https://w3techs.com/technologies/history_details/os-linux
    Usage statistics of operating systems for websites:        
        https://w3techs.com/technologies/overview/operating_system
    Ubuntu vs RHEL in enterprise computing:
        https://www.markshuttleworth.com/archives/1072