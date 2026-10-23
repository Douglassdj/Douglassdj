from pathlib import Path

content = """# Doug 👨‍💻

[![Instagram](https://img.shields.io/badge/Instagram-Instagram-0B1F33?style=flat&logo=instagram&logoColor=white)](SEU_LINK_INSTAGRAM) [![YouTube](https://img.shields.io/badge/YouTube-YouTube-0B1F33?style=flat&logo=youtube&logoColor=white)](SEU_LINK_YOUTUBE) [![LinkedIn](https://img.shields.io/badge/LinkedIn-LinkedIn-0B1F33?style=flat&logo=linkedin&logoColor=white)](SEU_LINK_LINKEDIN)

## Hello World! 🌎

Sou um profissional de tecnologia apaixonado por resolver problemas, melhorar processos e criar soluções úteis com tecnologia.

Também desenvolvo sites, landing pages e aplicações próprias. Gosto de aprender coisas novas, compartilhar conhecimento e transformar ideias em projetos reais. 🧑‍💻🚀

- 💻 Gosto de criar soluções que facilitem a vida das pessoas.
- ⚙️ Gosto de automatizar processos e encontrar maneiras melhores de fazer as coisas.
- 🌐 Desenvolvo sites e landing pages para apresentar negócios, serviços e produtos.
- 📱 Estou construindo aplicações web e mobile, incluindo o Think Capture.
- 📊 Sou apaixonado por dados, Power BI e inteligência de negócios.
- 🦆 Rubber Duck Debugging: às vezes, explicar o problema para o pato ajuda a encontrar a solução.

---
"""

path = Path("/mnt/data/README.md")
path.write_text(content, encoding="utf-8")
print(f"Arquivo criado: {path}")
