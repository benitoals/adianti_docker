# adianti_docker
Prepare a server for the Adianti Framework

Como usar:

Instale o Docker;
Execute o comando: $ docker run -d -p 80:80 -v /path/of/your/project:/var/www/html soluzionetecnologia/adianti-gabarito:latest
Acesse http://localhost

Observações:
Substitua /path/of/your/project pelo caminho do seu projeto no host;
Retirando o parâmetro -p o terminal fica retido no container exibindo os logs de "acessos" e "erros" do apache;
