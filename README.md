# COURSE 1 — Single Cell Sequencing / Spatial Transcriptomics

Minicurso sobre análise de dados de Single-Cell e Spatial Transcriptomics, ministrado em congresso de imunologia.

## 📚 Aulas

| Aula | Tema |
|------|------|
| 1 | User-Friendly Tools for Single-Cell and Spatial Transcriptomics |
| 2 | Reproducible Single-Cell and Spatial Analysis with R and Python |
| 3 | AI-Assisted Single-Cell and Spatial Analysis: Writing, Testing, and Improving Code |

## 📁 Estrutura do repositório

```
.
├── README.md
├── aula1/
├── aula2/
├── aula3/
└── docs/          <- (opcional, usado pelo GitHub Pages)
```

## 🚀 Como subir este repositório para o GitHub

1. Crie um repositório novo no GitHub (pode deixar vazio, sem README).
2. No seu computador, dentro da pasta do curso, rode:

```bash
git init
git add .
git commit -m "primeiro commit do curso"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/NOME-DO-REPO.git
git push -u origin main
```

> Troque `SEU-USUARIO` e `NOME-DO-REPO` pelos dados reais do seu repositório.

3. Se o repositório já existir e você só quiser atualizar arquivos:

```bash
git add .
git commit -m "atualiza material do curso"
git push
```

## 🌐 Como ativar o GitHub Pages

1. No repositório, vá em **Settings**.
2. No menu lateral, clique em **Pages**.
3. Em **Build and deployment**, selecione **Deploy from a branch**.
4. Escolha a branch `main` e a pasta `/root` (ou `/docs`, se você organizar os arquivos do site nessa pasta).
5. Clique em **Save**.
6. Aguarde 1–2 minutos e atualize a página — o link ficará disponível no formato:

```
https://SEU-USUARIO.github.io/NOME-DO-REPO/
```

## 📄 Licença

Defina aqui a licença do material (ex: MIT, CC-BY, ou "uso restrito ao congresso").
