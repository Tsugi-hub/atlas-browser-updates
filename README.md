# Atlas para Windows

Canal oficial de **instaladores e atualizações automáticas** do navegador Atlas. Este repositório não contém o projeto-fonte de desenvolvimento.

## Instalar

Abra a [versão mais recente](https://github.com/Tsugi-hub/atlas-browser-updates/releases/latest) e baixe `Atlas-Setup-<versão>-Windows-x64.exe`. Instale uma vez para receber as próximas versões pelo próprio navegador. O perfil local, favoritos, preferências e sessão anterior são preservados.

A edição instalada verifica novas versões ao abrir e a cada quatro horas. Baixa em segundo plano e aplica ao fechar normalmente; em **Configurações → Sobre o Atlas**, também é possível verificar, baixar e reiniciar para atualizar. A economia de internet adia o download automático.

## Integridade e limites

Cada lançamento contém o instalador, seu blockmap e `latest.yml` com SHA-512. O cliente aceita versões estáveis mais novas e verifica a integridade antes de executar o instalador. Downloads interrompidos ou inválidos não são instalados.

As distribuições atuais ainda podem não ter assinatura Authenticode; consulte as notas da versão. A atualização automática não elimina os avisos de reputação do Windows nem desativa suas proteções.

Somente instaladores e metadados de distribuição devem ser publicados aqui. Não publique código de desenvolvimento, perfis, cookies, credenciais, certificados privados ou logs pessoais.
