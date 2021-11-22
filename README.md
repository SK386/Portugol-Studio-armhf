# Portugol-Studio-armhf
Portugol Studio para dispositivos arquitetura arm(armhf)

Não sou responsavel por nenhum dos dados abaixo, os creditos pertecem a 
Luiz Fernando Noschang: perfil: https://github.com/noschang origem do comentario:https://github.com/UNIVALI-LITE/Portugol-Studio/issues/839

##################################################################################################################

Para isso, primeiro, baixe o JDK para ARM nesse link: https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html. Se você não tiver uma conta da Oracle será necessário criar uma antes de baixar.

Deves baixar a versão Linux ARM 32 Hard Float ABI ou a versão Linux ARM 64 Hard Float ABI, dependendo se o seu raspberry(ou outro dispositivo) para 32 ou 64 bits.

Depois de baixar o JDK, baixe essa versão aqui do Portugol Studio:
https://github.com/UNIVALI-LITE/Portugol-Studio/releases/download/v2.7.4/portugol-studio-2.7.4-linux-x64-standalone.zip

Após baixar os arquivos, sigas os seguintes passos:

Descompacte o arquivo do Portugol Studio

Acesse a pasta do Portugol Studio e vá até o diretório /portugol-studio/java

Apague a pasta /java-linux

Descompacte o arquivo do JDK dentro da pasta /portugol-studio/java

Renomeie a pasta do JDK de jdk1.8.0_261 para java-linux

Por fim certifique-se de que a estrutura de diretórios está da seguinte forma:

################################################################################
   
   
   -- portugol-studio-2.7.4-linux-x64-standalone
        -- arquivos-auxiliares
        -- portugol-studio
            -- java-linux
                -- bin
                -- include
                -- jre
                
                
################################################################################
Para executar o Portugol Studio, siga as instruções que se encontram no arquivo leia.txt na raiz da pasta do Portugol Studio.
