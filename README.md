### formulario-cadastro 
Foi selecionado o form por meio da " const form = document.getElementById" ;
Em seguida foi adicionado os inputs, selecionados pelos respectivos id's (username, email, password e password-confirmation) ; 
A linha form.AddEventListener('submit') foi usada para que a página não recarregar quando for enviado o formulário; 
A function checkInputs foi usada para que se verificasse os inputs e chamar funções que irão alterar a classe do formControl para error ou success ; 
Em seguida, foi verificado se o value do username é vazio, se for vazio ele vai chamar a função setErrorFor(username) e exibindo a mensagem de erro, essa função vai pegar o parentElement do input, foi feito para todos os inputs ;

