# Páginas de privacidade — Henriquescria

Publicado em `https://henriquescria.github.io/privacidade/`.

| Ficheiro | Para que serve |
|---|---|
| `index.html` | Política da **agência**, sobre a aplicação interna. É a que a Meta lê na revisão da app. |
| `termos.html` | Termos de serviço da mesma aplicação. |
| `modelo-cliente.html` | **Modelo** para a política de cada cliente, a que as pessoas leem antes de deixar o contacto num formulário de leads. |

## Porque é que cada cliente precisa da sua

A Meta **não deixa criar um formulário de leads sem um endereço de política de
privacidade**. Não é uma formalidade da app — é uma recusa da API, e o erro só
aparece no fim, depois de a campanha estar toda escrita.

Não vale a pena apontar para uma página genérica que não diga nada: quem preenche
o formulário está a entregar nome, telefone e email, e tem o direito de saber a
quem. Uma política que não descreva o tratamento real é exposição legal do
cliente, e é motivo para a Meta desativar o formulário se alguém se queixar.

Um cliente **com site próprio** deve tê-la no site dele — foi o que se fez com a
Carla, em `carlahenriques.pt/privacidade`. Este modelo é para os outros: quem não
tem site, ou tem um que não se consegue mexer.

## Como usar, em dois minutos

1. Copia o `modelo-cliente.html` para `<nome-do-cliente>.html`.
2. Substitui os cinco campos entre `[[ ]]`:
   - nome do negócio
   - NIF e morada
   - data de hoje
   - prazo de conservação dos dados (24 meses é um valor comum)
   - email de contacto para os pedidos de acesso e apagamento
3. `git commit` e `git push`. Fica em
   `https://henriquescria.github.io/privacidade/<nome-do-cliente>.html`.
4. Na app, ficha do cliente → **Links** → acrescenta esse endereço com o nome
   **"Política de Privacidade"**. O assistente de campanhas passa a preencher
   sozinho o campo da privacidade, porque procura um link com "privacidade" no
   nome.

## Antes de publicar

**Confirma com o cliente que o que lá está é verdade** — sobretudo o prazo de
conservação e o email de contacto, porque são promessas que ele terá de cumprir.
O modelo cobre o caso normal (formulário de leads, dados usados só para
contactar de volta, nada vendido a terceiros); se o cliente fizer mais alguma
coisa com os dados, isso tem de ficar escrito.

Isto é um ponto de partida honesto para o caso comum, não um parecer jurídico.
