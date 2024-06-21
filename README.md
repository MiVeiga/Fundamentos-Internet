# Entendendo URI, URL e URN

Como desenvolvedor frontend, é essencial compreender os conceitos de URI, URL e URN. Esses termos são fundamentais na web e, embora frequentemente utilizados de forma intercambiável, possuem significados distintos. Vamos explorar cada um desses conceitos e entender como eles se relacionam.

## O que é URI?

URI (Uniform Resource Identifier) é um identificador genérico para recursos na internet. Ele pode ser dividido em dois tipos principais: URL e URN. Em outras palavras, URI é um termo abrangente que inclui tanto URLs quanto URNs.

### Características do URI

- **Identificador de Recurso Uniforme (Uniform Resource Identifier)**
- **Função:** Identificar um recurso.
- **Abrangência:** Todos os URLs e URNs são URIs.
- **Esquemas:** Pode usar qualquer esquema (http, https, file, etc.).
- **Criação:** Você pode criar seu próprio URI, embora usar um nome de domínio registrado seja recomendado.

## O que é URL?

URL (Uniform Resource Locator) é um tipo de URI que, além de identificar um recurso, fornece um meio de localizá-lo especificando sua localização na rede. URLs são usadas diariamente para acessar sites na internet.

### Características do URL

- **Localizador de Recurso Uniforme (Uniform Resource Locator)**
- **Função:** Identificar e localizar um recurso.
- **Abrangência:** Todos os URLs são URIs. Nem todos os URIs são URLs. URLs não são URNs.
- **Esquemas:** O esquema especifica o protocolo para acessar o recurso.
- **Criação:** Você pode criar seu próprio URL, desde que controle seu nome de domínio.

### Exemplo de URL

https://www.github.com

Neste exemplo:
- `https` é o esquema, indicando que o protocolo usado é o HTTPS.
- `www.github.com` é o host, especificando o endereço do servidor onde o recurso está localizado.

## O que é URN?

URN (Uniform Resource Name) é um tipo de URI que identifica de forma única um recurso, sem indicar sua localização. URNs são mais comuns em contextos onde a persistência e a identificação única são mais importantes que a localização.

### Características do URN

- **Nome de Recurso Uniforme (Uniform Resource Name)**
- **Função:** Identificar um recurso.
- **Abrangência:** Todos os URNs são URIs. Nem todos os URIs são URNs. URNs não são URLs.
- **Esquemas:** Usa o esquema `urn`.
- **Criação:** URNs são geralmente atribuídos por organizações de padrões específicos.

### Exemplo de URN

urn:isbn:0451450523


Neste exemplo:
- `urn` é o esquema.
- `isbn:0451450523` é o identificador específico, indicando que este é um número de livro ISBN.

## Resumo e Relação entre URI, URL e URN

Para entender melhor como esses conceitos se relacionam, pense na URI como a categoria principal. URLs e URNs são subcategorias dentro dessa categoria. Cada URL e URN é uma URI, mas nem toda URI é necessariamente uma URL ou URN.

### Visualização da Relação

- URI
  - URL
  - URN


Por exemplo:
- `https://www.github.com` é uma URI e também uma URL.
- `urn:isbn:0451450523` é uma URI e também uma URN.

### Tabela Comparativa

| URI                               | URL                                   | URN                                   |
|-----------------------------------|---------------------------------------|---------------------------------------|
| Uniform Resource Identifier       | Uniform Resource Locator              | Uniform Resource Name                 |
| Identifica um recurso             | Identifica e localiza um recurso      | Identifica um recurso                 |
| Todos os URLs e URNs são URIs     | Todos os URLs são URIs. URLs não são URNs | Todos os URNs são URIs. URNs não são URLs |
| Pode usar qualquer esquema        | O esquema especifica o protocolo      | Usa o esquema `urn`                   |
| Pode criar seu próprio URI        | Pode criar seu próprio URL            | Geralmente atribuídos por organizações de padrões |

### Por que isso é Importante no Desenvolvimento Web?

Como desenvolvedor frontend, entender essas diferenças é crucial. URLs são usadas para criar links e referências a recursos, sejam eles APIs, imagens ou outros documentos. Saber como construir e interpretar URIs ajuda na comunicação clara com servidores e no desenvolvimento de aplicações web robustas e seguras.

---

Espero que este artigo tenha ajudado a esclarecer os conceitos de URI, URL e URN de forma clara e estruturada. Se tiver qualquer dúvida ou quiser discutir mais sobre o assunto, sinta-se à vontade para abrir uma issue ou entrar em contato!
