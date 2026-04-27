* Pedidos | SZAC-DEV

tava madrugando nem sei oque isso faz direito.

## 🛠️ Tecnologias e Arquitetura

O projeto utiliza **Python** como base, seguindo um padrão de organização modular para facilitar a manutenção e escalabilidade:

* **Linguagem:** Python 3.x
* **Framework:** [Flask/Django - *ajustar se necessário*]
* **Banco de Dados:** Gerenciado via diretório `Modelos` e `Migrações`.
* **Frontend:** Arquivos em `estática` (CSS, JS, Imagens).

## 📂 Estrutura do Projeto

* `/Instância`: Configurações de ambiente e instância do banco de dados.
* `/Migrações`: Histórico de evolução do esquema do banco de dados.
* `/Modelos`: Definições das entidades de dados (Pedidos, Clientes, Produtos).
* `/estática`: Assets e recursos estáticos do sistema.
* `app.py`: Ponto de entrada da aplicação.

## 🚀 Como Executar o Projeto
(se e que alguem vai usar isso, acho que se terminar da pra tirar grana freelancer)
### 1. Clonar o Repositório
```bash
git clone [https://github.com/SZAC-DEV/pedidos.git](https://github.com/SZAC-DEV/pedidos.git)
cd pedidos
2. Configurar Ambiente Virtual
Bash
python -m venv .venv
# No Windows:
.venv\Scripts\activate
# No Linux/Mac:
source .venv/bin/activate
3. Instalar Dependências
Bash
pip install -r requirements.txt
4. Rodar a Aplicação
Bash
python app.py
