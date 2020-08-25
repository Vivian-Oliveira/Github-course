# Git Course

Este é um repositório teste para aprender como o git funciona.
Muito legal, estou comecando a entender hehehehe!

Tutorial do GIT Básico – Introdução ao GIT
Os sistemas de controle de versão são uma ótima forma de prevenir que você arranque seus cabelos sempre que tentar analisar as alterações feitas em um código de projeto compartilhado. Simplificando, um VCS (sigla para version control system) é um componente fundamental do sistema de gerenciamento de configuração de software que cuida das mudanças que precisam ser feitas em um projeto. As alterações/revisões/ atualizações feitas são identificáveis ​​através de códigos de letra ou números. Informações como data e a identidade do autor da alteração também são mantidas.

Neste tutorial, vamos falar sobre um dos sistemas de controle de versão mais usados no mundo ​​- o GIT. Você aprenderá o básico do GIT, por exemplo, como instalar o GIT em sistemas diferentes e como usá-lo corretamente.

Conteúdo

O que é GIT?
1º Passo – Instalar o GIT em Sistemas Diferentes
2º Passo – Como Usar o GIT
Fluxo de trabalho
Conclusão
O que é GIT?
Em 2005, Linus Torvalds (o homem conhecido por criar o núcleo, ou kernel, do SO Linux) desenvolveu o GIT, que desde então tem sido ativamente mantido por Junio ​​Hamano, um engenheiro de software japonês. Atualmente, o GIT é um dos mais famosos sistemas de controle de versão de código aberto e milhões de projetos no mundo inteiro o utilizam para seu controle de versão (incluindo projetos comerciais e de código aberto). O Git é totalmente grátis e pode ser instalado em Mac, Linux, Windows e Solaris diretamente do site oficial . Algumas das características essenciais do GIT são:

Um sistema de controle de versão distribuído, o GIT segue uma abordagem peer to peer, contrário de outros como o Subversion (SVN) que segue um modelo baseado em cliente-servidor.
GIT permite aos desenvolvedores ter uma infinidade de ramos de código completamente independente. Criação, exclusão e fusão desses ramos é simples e não leva tempo.
No GIT, todas as operações são atômicas. Isso significa que uma ação pode ter sucesso ou falhar (sem fazer nenhuma alteração). Isso é importante porque em alguns sistemas de controle de versão (como o CVS) onde as operações não são atômicas, se uma operação de repositório é suspensa, ela pode deixar o repositório em um estado instável.
No GIT, tudo é armazenado dentro da pasta .git. Isso não é o mesmo em outros VCS como SVN e CVS onde os metadasdados de arquivos são armazenados em pastas ocultas (por exemplo, .cvs, .svn, etc.)
GIT usa um modelo de dados que ajuda a garantir a integridade criptográfica de qualquer coisa presente dentro de um repositório. Cada vez que um arquivo é adicionado ou um commit é feito, suas somas de verificação são geradas. Da mesma forma, eles são recuperados através de suas somas de verificação também.
Outra característica presente no GIT é sua área de teste ou índice. Na área de preparação, os desenvolvedores podem formatar commits e receber feedback ​​antes de aplicá-los.
O GIT é consideravelmente simples de usar. Para começar, você pode criar um repositório ou conferir um já existente. Após a instalação, um simples git-init irá deixar tudo pronto. Da mesma maneira, o comando git clone pode criar uma cópia de um repositório local para um usuário.

fonte: https://www.hostinger.pt/tutoriais/tutorial-do-git-basics-introducao/
