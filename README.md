from pathlib import Path

content = """<div align="center">

# Doug 👨‍💻
### 🦆 Rubber Duck Debugging Mode: ON

*Transformando problemas em soluções com tecnologia.*

</div>

---

## Sobre mim

Sou um profissional de tecnologia apaixonado por resolver problemas, melhorar processos e transformar ideias em soluções digitais.

- 📊 **Dados e BI:** análise de dados, Power BI e inteligência de negócios.
- ⚙️ **Automação:** melhoria contínua e automação de processos.
- 🌐 **Desenvolvimento web:** criação de sites e landing pages.
- 📱 **Aplicações:** desenvolvimento de projetos web e mobile.
- 💡 **Criação de produtos:** explorando ideias e transformando-as em soluções úteis.
- 🌱 **Aprendizado contínuo:** sempre aprendendo, construindo e evoluindo.

## Projeto em destaque

### 📱 Think Capture

Um aplicativo criado para capturar pensamentos e organizar ideias, ajudando a tirar coisas da cabeça sem precisar decidir tudo na mesma hora.

> Acredito que a tecnologia deve simplificar problemas, conectar ideias e criar oportunidades.

---

<div align="center">

*Building, learning, and improving — one project at a time.*

</div>
"""

path = Path("/mnt/data/README.md")
path.write_text(content, encoding="utf-8")
print(f"Arquivo atualizado: {path}")
