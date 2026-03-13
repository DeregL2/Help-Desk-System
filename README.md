# 🛠️ HelpDesk System

Um sistema moderno de suporte técnico e gerenciamento de chamados desenvolvido com **Python (Flask)**. O projeto foca em oferecer uma interface intuitiva para o usuário final e camadas robustas de segurança para a proteção de dados.

## 🚀 Funcionalidades Principais

### **Gestão de Chamados (Tickets)**
* **Dashboard Dinâmico:** Painel centralizado para visualização de atividades recentes e status do sistema.
* **Visualização via Modal:** Os detalhes de cada ticket podem ser abertos em janelas flutuantes (modais), permitindo uma navegação rápida sem sair da lista principal.
* **Organização Profissional:** Lista de tickets com separação por colunas de Assunto, Solicitante, Status e Data de Criação.
* **Filtros Inteligentes:** Sistema de busca e filtragem por status (Aberto, Em andamento, Fechado).

### **Segurança e Privacidade**
* **Criptografia com BCrypt:** As senhas dos usuários são transformadas em hashes seguros antes de serem salvas, garantindo que dados sensíveis nunca fiquem expostos.
* **Autenticação de Dois Fatores (2FA):** Camada extra de segurança que exige um código de 6 dígitos enviado ao e-mail do usuário para validar o acesso.
* **Validação Rigorosa:** O cadastro exige senhas fortes com letras maiúsculas, minúsculas, números e caracteres especiais.
* **Conformidade (LGPD):** Inclui box de aceite de termos de uso e política de privacidade no momento do cadastro.

### **Interface (UI/UX)**
* **Design Responsivo:** Layout adaptável para dispositivos móveis, tablets e desktops.
* **Floating Action Button (FAB):** Botão flutuante estilizado para criação rápida de novos tickets.
* **Zona de Perigo:** Área específica para exclusão de conta com confirmação por senha para evitar ações acidentais.

---

## 💻 Tecnologias Utilizadas

* **Backend:** Python com Framework Flask.
* **Banco de Dados:** SQLAlchemy (ORM) para manipulação de dados de usuários e tickets.
* **Frontend:** HTML5, CSS3 moderno (Flexbox e Grid) e JavaScript puro.
* **Segurança:** Biblioteca `bcrypt` para hashing de senhas.
