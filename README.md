# minutas — endereco fixo do Validador

Este repositorio existe por **um** motivo: dar um endereco que nao muda para o
Validador de Minutas da Girollar.

O sistema roda no notebook do escritorio, exposto por um *quick tunnel* do Cloudflare,
cujo endereco e **sorteado a cada reinicio do tunel**. Quem guardasse o link perderia o
acesso na primeira queda. A pagina aqui redireciona para o endereco vigente, e o proprio
notebook a republica sempre que o tunel troca de URL.

**Link fixo:** https://girollarcom4.github.io/minutas/

Nao ha codigo nem dado do sistema aqui — so o redirecionamento. O acesso continua exigindo
login: sem credencial, todas as rotas respondem 401 ou devolvem para a tela de entrada.

Publicado por `scripts/publicar-link-tunel.ps1`, no repositorio `validador-minutas`.
