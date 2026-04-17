alejandro@alejandro-HP-Laptop-15-fc0xxx:~$ mkdir Master1
alejandro@alejandro-HP-Laptop-15-fc0xxx:~$ cd Master1
alejandro@alejandro-HP-Laptop-15-fc0xxx:~/Master1$ git init 
Inicializado repositorio Git vacío en /home/alejandro/Master1/.git/
alejandro@alejandro-HP-Laptop-15-fc0xxx:~/Master1$ touch README.md
alejandro@alejandro-HP-Laptop-15-fc0xxx:~/Master1$ git add .
alejandro@alejandro-HP-Laptop-15-fc0xxx:~/Master1$ git commit -m "primer desarrollo"
[alejandro (commit-raíz) 4bb96ec] primer desarrollo
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
alejandro@alejandro-HP-Laptop-15-fc0xxx:~/Master1$ git branch -M main 
alejandro@alejandro-HP-Laptop-15-fc0xxx:~/Master1$ git remote add origin https://github.com/alejandro0997272352/Master1.git
alejandro@alejandro-HP-Laptop-15-fc0xxx:~/Master1$ git push -u origin main 
Username for 'https://github.com': alejandro0997272352
Password for 'https://alejandro0997272352@github.com': 
remote: Invalid username or token. Password authentication is not supported for Git operations.
fatal: Autenticación falló para 'https://github.com/alejandro0997272352/Master1.git/'
alejandro@alejandro-HP-Laptop-15-fc0xxx:~/Master1$ git push -u origin main 
Username for 'https://github.com': alejandro0997272352
Password for 'https://alejandro0997272352@github.com': 
Enumerando objetos: 3, listo.
Contando objetos: 100% (3/3), listo.
Escribiendo objetos: 100% (3/3), 219 bytes | 219.00 KiB/s, listo.
Total 3 (delta 0), reusados 0 (delta 0), pack-reusados 0
To https://github.com/alejandro0997272352/Master1.git
 * [new branch]      main -> main
rama 'main' configurada para rastrear 'origin/main'.
alejandro@alejandro-HP-Laptop-15-fc0xxx:~/Master1$ 
