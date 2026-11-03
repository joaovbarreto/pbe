<div align="center">

# 📚 PBE · Indicações

**Livros, fontes de evidência e perfis indicados pelo psicólogo [João Paulo Eras](https://www.instagram.com/joaopauloeras/) na entrevista do Estágio Básico I sobre Prática Baseada em Evidências.**

[![Site](https://img.shields.io/badge/ver%20o%20site-joaovbarreto.github.io%2Fpbe-1F6FB2?style=for-the-badge)](https://joaovbarreto.github.io/pbe/)
![HTML](https://img.shields.io/badge/HTML%20%2B%20CSS-sem%20depend%C3%AAncias-E07B39?style=for-the-badge)
![Mobile first](https://img.shields.io/badge/mobile-first-16213A?style=for-the-badge)

<img src="img/joao-paulo.jpg" alt="João Paulo Eras" width="140">

</div>

---

## ✨ Sobre

Página única, pensada para o celular, que reúne tudo o que foi recomendado na entrevista:

- 📖 **Livros** de Prática Baseada em Evidências, formulação de caso, protocolos clínicos e DBT
- 🔬 **Fontes de evidência** (Cochrane Library, APA Division 12, OQ-Measures)
- 👤 **Perfis** de profissionais para acompanhar
- 🧭 Telas da **SevnIA**, ferramenta de IA que o entrevistado desenvolve (formulação de caso, eventos, supervisão e cartão do paciente)

Tem **modo escuro automático** (segue o tema do dispositivo) e carrega rápido: é HTML e CSS, com algumas linhas de JavaScript só para ampliar as imagens. Sem frameworks nem build.

## 🎓 Contexto

Material de apoio da apresentação oral da disciplina **Estágio Básico I** do curso de Psicologia da Estácio Ribeirão Preto. O grupo entrevistou o psicólogo clínico João Paulo Eras Silva (CRP 06/186353) em 12/09/2026, e a turma acessa esta página por um QR code no fim da apresentação.

O conteúdo foi publicado com autorização do entrevistado. O paciente que aparece nas telas da SevnIA é fictício, criado por ele para testes.

## 🌐 Acesse

👉 **<https://joaovbarreto.github.io/pbe/>**

## 🗂️ Estrutura

```
.
├── index.html     # a página inteira (HTML, CSS e um script de zoom)
├── img/           # capas dos livros, foto e telas da SevnIA
├── .nojekyll      # publica os arquivos como estão, sem Jekyll
└── README.md
```

## 💻 Rodar localmente

Não há nada para instalar. Abra o `index.html` no navegador ou, se preferir um servidor local:

```bash
python3 -m http.server 8000
```

e acesse <http://localhost:8000>.

## 🚀 Publicação

O site é servido pelo **GitHub Pages** a partir da branch `main` (pasta raiz). Para atualizar, basta editar os arquivos e fazer commit em `main`: em cerca de um minuto a mudança estará no ar.

## 👤 Autor

Feito por [João Barreto](https://github.com/joaovbarreto).
