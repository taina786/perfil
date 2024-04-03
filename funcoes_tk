localFoto = document.getElementById('fotododitocujo');
localFoto.src = user.photos[1];

outraFoto = document.getElementById('fotodadireita');
outraFoto.src = user.photos[0];

localNome = document.getElementById('nomeDoMeliante');
localNome.innerHTML = user.nome;

localInformação = document.getElementById('informaçãoDoMeliante');
localInformação.innerHTML = user. informação;

localsexo = document.getElementById('sexoDoMeliante');
localsexo.innerHTML = user. sexo;

localDataDeNascimento = document.getElementById('DataDeNascimentoDoMeliante');
localDataDeNascimento.innerHTML = user. DataDeNascimento;

localpais = document. getElementById('paisdomeliante');
localpais.innerHTML = user. pais;

localirmãos  = document. getElementById('irmãosdomeliante');
localirmãos.innerHTML = user. irmãos;

localcidade = document. getElementById('cidadedomeliante');
localcidade.innerHTML = user. cidade;

localcidadenatal = document. getElementById('cidadenataldomeliante'),
localcidadenatal.innerHTML = user. cidadenatal;

localbio = document. getElementById('biodomeliante');
localbio.innerHTML = user. bio;

localfrasefavorita = document. getElementById('frasefavoritadomeliante');
localfrasefavorita.innerHTML = user. frasefavorita;

localAmigosÍntimos = document. getElementById('AmigosÍntimosdomeliante');
localAmigosÍntimos.innerHTML = user. AmigosÍntimos;

primeironome = document.getElementById("primeiroNome");
primeironome.innerHTML = user.nome.split(' ')[0];


function montarPostagem(mensagem)
{
    let postagem = '<p class="post">';
    postagem += mensagem;
    postagem += "</p>";
    postagem += '<p class="likeArea">';
    postagem += '<a class="likeButton">curtir</a>';
    postagem += '<a class="likeButton">compartilhar</a>';
    postagem += '<a class="likeButton">denunciar</a>';
    postagem += "</p>";
    return postagem;
}

postagens = document.getElementById('postagens');
for (var i = 0; i < user.postagens.length; i++) {
    postagens.innerHTML+= montarPostagem(user.postagens[i]);
}

function showSelectedDate()
{
    let data = document.getElementById("inputCalendario").value;
    document.getElementById("selectedDate").innerHTML = data;
}