# Como configurar a integração do seu repositório do *GitHub* com o *Power Apps*.

1. No *Power Apps* acesse o Aplicativo desejado.
   
1. Na tela de edição do aplicativo clique em `configurações` na parte superior da tela (Se estiver pelo navegador ela pode estar na aba `...`).
   
   ![config power apps](https://github.com/xLeoGia5/power-platform/assets/138023684/c482d505-889e-477e-bcd2-70d808221803)
   
1. Acesse a opção `Recursos Futuros`.

    I. Como a integração do *Power Apps* com o *GitHub* ainda está em versão experimental, precisa-se ativar uma configuração na aba `Experimental` que fica logo abaixo da barra de Pesquisa.

   ![config exp](https://github.com/xLeoGia5/power-platform/assets/138023684/c54e813d-e521-411a-9de4-100e79f790cc)

1. Descendo a barra de rolagem na aba experimental, ative a opção `Mostrar a configuração de controle da versão Git`.
   
   I. Isso habilitará mais uma opção de configuração, acesse `Controle de versão Git`.
   
   ![coonfig git](https://github.com/xLeoGia5/power-platform/assets/138023684/742e5b4b-e54c-4595-a89e-30162902a87d)
   
   II. Clique em `Conectar` (Onde serão requeridas as informações referentes ao repositório que se quer fazer a integração).
   
      ![inf deploy](https://github.com/xLeoGia5/power-platform/assets/138023684/208e18dc-ea9e-4572-8ed3-5dbba3aefaa3)
   
   * URL do repositório Git: No GitHub, copie a URL do repositório desejado.
  
     ![git url](https://github.com/xLeoGia5/power-platform/assets/138023684/2f513f6c-d7e5-462d-8956-4df11fc80ed9)
  
   * Ramificação: A Branch (ramificação) em que se deseja fazer a integração.
  
   * Nome do diretório: Nome que se deseja usar para o repositório. ( Caso queira que o diretório seja criado dentro de outro diretório devera colocar a informação da seguinte maneira ./nome-do-diretorio/nome-do-aplicativo ).

   `OBS: Pode-se usar o mesmo repositório dentro da mesma *Branch* para vários aplicativos diferentes.`

   III. Preenchidas as informações do repositório, serão requeridas suas credenciais de acesso. (Também há a opção de criar uma chave de acesso específica para esse aplicativo, que será colocada no lugar da senha, onde pode-se definir quais arquivos a chave terá acesso e tempo de expiração da chave, que, ao expirar, exigirá que a integração seja reconfigurada).

   * Para isso, acesse as configurações da sua conta do GitHub, vá em `Developer settings` (No final da barra de rolagem).
   * Acesse a aba `Personal access tokens`.
   * Opção `Tokens (classic)`.
   * Em seguida, clique em `Generate new token`.
  
     ![key git](https://github.com/xLeoGia5/power-platform/assets/138023684/b5fdd08d-d329-4696-8aeb-003afcc84f1c)

   * Nomeie e configure o tempo de permanência de ativação da chave de acesso e as permissões que desejar (A única necessária é a de acesso ao repositório que deseja fazer a integração).
   * E clique em `Generate token` (no final da barra de rolagem).
   * Copie a chave de acesso gerada.
  
     ![key git2](https://github.com/xLeoGia5/power-platform/assets/138023684/870a9c5e-3ccf-48df-bd7f-aace3d5ee736)
     

   * Cole no lugar de onde seria sua senha, ao passar as credenciais do *GitHub* para o *Power Apps*.

   * Após isso, clique em `Entrar`.
  
     ![login apps](https://github.com/xLeoGia5/power-platform/assets/138023684/62795508-2b58-4ebc-8671-deaff7424517)

  
   * Se for a primeira vez que o processo for feito, o *Power Apps* identificará que o diretório informado não existe na *Branch* desejada e perguntará se gostaria de criar um novo. Basta clicar em `Sim`.

1. Pronto, agora o Aplicativo já está conectado ao repositório desejado do *GitHub*.

