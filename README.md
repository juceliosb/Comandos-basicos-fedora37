# Comandos-basicos-fedora37
Seja bem vindo ao mundo linux se você esta começando nele através do **_Fedora_**, ou esta migrando de uma outra distro como o **_Ubunntu ou Mint_** etc. Pode ter certeza que esses comandas vão lhe ajudar muito na sua jornada do **_"Chapeu Azul"_**.

## Atualizando o Sistema
Apos instalar o **_Fedora_** é muito importante atualizá-lo, para receber novas versões dos pacotes, softwares recentes bem como atualização de segurança e correções de erros.

> ```sudo dnf upgrade```

## Para quem gosta de trabalhar na sua lingua

Mesmo selecionando o idioma "Português" durante a instalação do Fedora e na tela de pré-configuração após a instalação do mesmo, alguns programas, como o LibreOffice, ainda ficam em inglês. Para resolver isso, devemos instalar o pacote "system-config-language", abra um terminal e tecle:


> ```sudo dnf install system-config-language```

Após execultar o comando em seguida o outro

>```system-config-language```

Será exibido a janela de seleção de idioma.

Após o download dos pacotes de idioma, aparecerá um aviso informando que o suporte ao idioma está instalado, clique em "OK" para defini-lo como idioma padrão do sistema: