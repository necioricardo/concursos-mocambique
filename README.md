# Concursos Moçambique (site estático)

Hugo, tema próprio mínimo, sem JavaScript, sem cookies.

- Novo concurso: ficheiro em `content/concursos/<slug>.md` (campos: title, description, slug, date, entidade, sectores, numero, prazo, prazo_texto, valor, quem_pode, link_oficial, link_rotulo, recolha, estado).
- Estado passa a "expirado" automaticamente no build quando o prazo passa; o campo `estado` também é actualizado na rotina diária. Nunca apagar páginas.
- Cloudflare Pages: preset Hugo, comando `hugo --minify`, pasta `public`, variável `HUGO_VERSION=0.139.4`.
- Nunca guardar senhas ou tokens neste repositório.
