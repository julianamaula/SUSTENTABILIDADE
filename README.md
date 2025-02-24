# Vídeos Incorporados


## 1. Outro Vídeo

Aqui está outro vídeo interessante:

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/dCOOWSbe6Ig"></iframe>
</div>

### Metadados:
- **Título**: Outro Vídeo
- **URL**: [https://www.youtube.com/embed/dCOOWSbe6Ig](https://www.youtube.com/embed/dCOOWSbe6Ig)
- **Descrição**: Vídeo sobre outro tópico interessante.
- **Produto**: Projects
- **Versões**: fpt, GHES > 3.2
- **Data de adição**: 2023-10-01
- **Localização**: /docs/another-topic
- **Transcrição**: [Ver transcrição](./content/video-transcripts/outro-video.txt)

---

## 2. Vídeo no Dailymotion

Aqui está um vídeo hospedado no Dailymotion:

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.dailymotion.com/embed/video/x3zefbo"></iframe>
</div>

### Metadados:
- **Título**: Vídeo no Dailymotion
- **URL**: [https://www.dailymotion.com/embed/video/x3zefbo](https://www.dailymotion.com/embed/video/x3zefbo)
- **Descrição**: Vídeo hospedado no Dailymotion.
- **Produto**: Projects
- **Versões**: fpt, GHES > 3.2
- **Data de adição**: 2023-10-01
- **Localização**: /docs/dailymotion
- **Transcrição**: [Ver transcrição](./content/video-transcripts/dailymotion-video.txt)

## 3. Aprendendo se divertindo

Aqui está um vídeo sobre como aprender de forma divertida:

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/18NoW5UTstk"></iframe>
</div>

### Metadados:
- **Título**: Aprendendo se divertindo
- **URL**: [https://www.youtube.com/embed/18NoW5UTstk](https://www.youtube.com/embed/18NoW5UTstk)
- **Descrição**: Vídeo sobre como aprender de forma divertida.
- **Produto**: Projects
- **Versões**: fpt, GHES > 3.2
- **Data de adição**: 2023-10-01
- **Localização**: /docs/learning
- **Transcrição**: [Ver transcrição](./content/video-transcripts/aprendendo-se-divertindo.txt)


# Repositório de Vídeos

Este repositório contém metadados de vídeos incorporados na documentação.

## Estrutura do Repositório

- `.github/workflows/main.yml`: Fluxo de trabalho para validar metadados de vídeos.
- `docs/metadata/videos.yml`: Arquivo YAML com os metadados dos vídeos.
- `css/`: Pasta com arquivos CSS.

## Como Adicionar um Novo Vídeo

1. Edite o arquivo `docs/metadata/videos.yml`.
2. Adicione os metadados do novo vídeo no formato YAML.
3. Faça commit e push das alterações.
4. O fluxo de trabalho será acionado automaticamente para validar o arquivo YAML.

## Fluxo de Trabalho

O fluxo de trabalho valida o arquivo `videos.yml` e garante que ele esteja no formato correto.
