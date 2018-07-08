![Alt text](https://github.com/diegoMasin/maximumtech/blob/master/assets/img/logo-colorida.png)<br>

Empresa de Desenvolvimento de Software.

# Padrão de projeto Django Aquarela85
Aquarela85 começou como um projeto de gestão comercial. Contudo o nome foi trocado pois este nome já pertencia a outra empresa.
No início do processo de desenvolvimento, esse projeto já estava no ponto chave de começar os cruds do projeto. 
Mesmo assim, já estava implementado layout, login e logout com cadastro de usuário, logo a partir daí foi denominado que Aquarela85 seria o marco para se construir projetos futuros em Django servindo como padrão e base para o início de qualquer novo projeto.

## Seguirá aqui abaixo os passos que serão necessários toda vez que for criado um novo projeto do zero usando este padrão.

*Criar o repositório do seu novo projeto. Copiar para dentro dele a branch master da aquarela85 sem a pasta idea, se houver.
*Commitar e já realizar o primeiro push do seu novo projeto para não sobrecarregar ou misturar as alterações a seguir.
*Alterar a pasta interna com nome de aquarela85 para o nome do seu projeto.
*Abri o arquivo settings e alterar em todo lugar que houver aquarela85 para o nome do seu projeto(atenção especial ao schema configurado que nao tem o 85).
*Fazer um find path em todo o sistema em busca do nome aquarela85 e substituir pelo nome do seu projeto.
*É interessante sempre gerar uma secret key nova para cada projeto. Até onde não se sabe não interfere no projeto. Vide: https://www.miniwebtool.com/django-secret-key-generator/
*Criar a virtualenv pelo pycharm: Acesse o interpreter; add local; new environment; coloque o nome da virtual, escolhendo o local onde será crida(geralmente como irmão da pasta do projeto) e não mexer no campo base; click OK.
*Após clicar em ok em tudo, surgirá ao topo da IDE uma opção para instalar os requirements detectados no arquivo txt dentro do projeto. Se não aparecer, entre no arquivo settings que aparecerá.
*Configure o Start Server
*Instale o Dict InteliJ português(spelling)
*Vá no Banco postgress, crie uma database com o nome do seu projeto, e um schema também com o mesmo nome.
*Rode o migrate
*No terminar crie um primeiro usuário admin padrão root com: python manage.py createsuperuser
*Teste a aplicação funcionando local
*Até aqui projeto funcionando com Sucesso. Só alterar depois detalhes de layout que ainda tenha o nome Aquarela85
*Commit e Pushed seu segundo commit e ultimo, agora só começar a desenvolver.
*SUCESS!