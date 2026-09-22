# ⚡ Galp Telegestão | Engenharia & Tecnologia

Bem-vindo ao perfil oficial de engenharia da **Galp Telegestão**. Desenvolvemos ecossistemas completos de **Telegestão e IoT**, integrando Hardware, Firmware embarcado e Software de alta confiabilidade.

📚 **Documentação Central de Engenharia:** [Acessar Wiki no Notion](https://app.notion.com/p/3c78ec8c84518018ac54d03fc26b38e4?v=3c78ec8c84518088b35d000c4a5b7627&source=copy_link)

---

## ⚙️ Nossos Pilares de Engenharia

* **Eletrônica & Hardware (`hw-`):** Circuitos de potência, comunicação, sensoriamento, layout de PCBs e modelagem mecânica 3D.
* **Firmware Embarcado (`fw-`):** Desenvolvimento de baixo nível em RTOS e bare-metal, protocolos industriais e conectividade (BLE, LoRaWAN, Celular).
* **Software & Plataforma (`sw-`):** Ferramentas de testes de bancada, scripts de calibração, APIs e aplicações de suporte.

---

## 📌 Regras Básicas do Uso do Repositório

Para manter o fluxo de trabalho padronizado entre os times multidisciplinares (Hardware, Firmware e Produção), siga rigorosamente as diretrizes abaixo:

1. **Uso Obrigatório dos Templates da Empresa:**
   * Todo novo repositório deve ser criado contendo os modelos oficiais de `README.md` e `CONTRIBUTING.md`.
2. **Nomenclatura Padrão de Repositórios:**
   * `hw-[nome-do-produto]`: Esquemáticos, layout PCB e CAD mecânico.
   * `fw-[nome-do-produto]`: Código-fonte para microcontroladores e processadores.
   * `ma-[nome-do-produto]`: Modelos 3D, desenhos conceituais do produto. 
   * `sw-[nome-do-produto]`: Softwares auxiliares, ferramentas CLI ou dashboards.
   * `[nome-do-produto]`: Projeto com ambos hardware e software seguindo o template.
3. **Controle de Versão e Integridade:**
   * Proibido realizar *commit* ou *push* direto nas branches `main` ou `develop`.
   * Todo código ou projeto precisa passar por **Pull Request (PR)** com aprovação de pelo menos 1 revisor da área responsável.
   * Commits devem seguir o padrão *Conventional Commits* (ex: `feat(fw): ...`, `hw(schematic): ...`).
  
4. **Regras de nomenclaturas de branches**
   * `main`: Versão válida em funcionamento
   * `dev`: Linha principal de trabalho aonde todos os commits deverão ser feitos através de pull requests.
   * `feat`: Para coisas novas (ex: `feat: adiciona detecção de velocidade`)
   * `fix`: Para correções (ex: `fix: corrige falha no script de build`)
   * `ref`: Para reescrita de código sem alterar o que ele faz.
   * `docs`: Para atualização em documentação ou README.
   * `chore`: Criação um feature ou ref que não estava especificado (evitar).

4. **Documentação e Centralização (Wiki):**
   * Decisões arquiteturais de grande impacto (ADRs), estudos de viabilidade e histórico de pesquisa **não devem ficar isolados** nos repositórios. Registrar sempre na [Wiki do Notion](https://app.notion.com/p/3c78ec8c84518018ac54d03fc26b38e4?v=3c78ec8c84518088b35d000c4a5b7627&source=copy_link) e referenciar o link no `README` do projeto.

---

## 🛠️ Matriz de Ferramentas e Stacks da Empresa

| Domínio | Ferramentas & Softwares | Arquivos / Formatos |
| :--- | :--- | :--- |
| **Mecânica & 3D** | FreeCAD | `.step`, `.f3d`, `.sldprt` |
| **Eletrônica & PCB** | KiCad | Schematics, Gerbers, BOM |
| **Firmware Embarcado** | VS Code, ESP-IDF, STM32Cube, FreeRTOS | C, C++, Assembly |
| **Software Auxiliar** | Python, Node.js, Docker | `.py`, `.js`, Dockerfile |
| **Gestão & Docs** | GitHub Projects, Notion Wiki | Markdown, Notion Docs |

---

📫 **Suporte Interno:** Para solicitar a criação de novos repositórios ou tirar dúvidas sobre acessos, entre em contato com a **Liderança de Engenharia**.
