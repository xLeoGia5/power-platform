# Como configurar o *Deploy* do *GitHub* com o *Power Apps*

1. No *Power Apps* acesse o Aplicativo desejado.
   

1. Na tela de edição do aplicativo clique em `configurações`  na parte superior da tela ( se estiver pelo navegador ela pode estar na aba `...`  ).
   
   ![config power apps](https://github.com/xLeoGia5/power-platform/assets/138023684/c482d505-889e-477e-bcd2-70d808221803)
   

1. Acesse a opção `Recursos Futuros`.

    I. Como a integração do *Power Apps* com o *GitHub* ainda está em versão experimental, precisa-se ativar uma configuração na aba `Experimental`que fica logo a baixo da barra de Pesquisa.

   ![config exp](https://github.com/xLeoGia5/power-platform/assets/138023684/c54e813d-e521-411a-9de4-100e79f790cc)



1. Descendo a barra de rolagem na aba experimental, ativee a opção ` Mostrar a configuração de controle da versão Git `  .
   

   I. Que habilitara mais uma opção de configuração, acesse ` Controle de versão Git ` .

   
   ![coonfig git](https://github.com/xLeoGia5/power-platform/assets/138023684/742e5b4b-e54c-4595-a89e-30162902a87d)
   

   II. Clique em  `Conectar` ( onde serão requeridas as informações referentes o repositorio que se quer fazer a integração).
   

      ![inf deploy](https://github.com/xLeoGia5/power-platform/assets/138023684/208e18dc-ea9e-4572-8ed3-5dbba3aefaa3)
   

   * URL do repositório Git: No github copie a URL do repositorio desejado .
  
     ![git url](https://github.com/xLeoGia5/power-platform/assets/138023684/2f513f6c-d7e5-462d-8956-4df11fc80ed9)
  
   * Ramificação: A Branch ( raminicação ) se que fazer a integração.
  
   * Nome do diretório: Nome que se deseja usar para o repositorio.
  
   III. Preenchidas as informações do repositorio, sera requerida suas credenciais de acesso. ( Também à a opção de criar uma chave de acesso especifica para esse aplicativo, que sera colocada no lugar da senha, onde pode-se definir  quais arquivos a chave tera acesso e tempo de expiração da chave que em seu termino a integração tera que ser reconfigurada ).

   * Para isso acesse as configurações da sua conta do GitHub va em ` Developer settings ` ( no final da barra de rolagem )
   * Acesse a aba ` Personal acess tokens ` .
   * Opção ` Tokens (classic) ` .
   * Depois em ` Generate new token `.
  
     ![key git](https://github.com/xLeoGia5/power-platform/assets/138023684/b5fdd08d-d329-4696-8aeb-003afcc84f1c)


  

1. 
