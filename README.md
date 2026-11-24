# LP do evento Logos CS + Fox Human Capital (9/12/2026)

Site estático (HTML, imagens e fontes locais). Publicar a pasta inteira, sem build.

## Ao mudar de domínio
O endereço público aparece em 5 arquivos: `index.html` (canonical, og:url, og:image, twitter:image, JSON-LD), `robots.txt`, `sitemap.xml` e `llms.txt`.
Para trocar tudo de uma vez (Linux/Mac/Git Bash):

    grep -rl "erik-akaishi.github.io/logos-cs-evento26/" . | xargs sed -i 's#https://erik-akaishi.github.io/logos-cs-evento26/#https://NOVO-ENDERECO/#g'

## Pendências de conteúdo
Link do Microsoft Forms (bloco tracejado em "Garanta sua vaga"), apresentador da Fox, política de privacidade e perguntas do FAQ marcadas com [a confirmar].
