# Tradutor de Documentos DOCX

Este script Python utiliza o serviço **Azure AI Translator** e as bibliotecas `requests` e `python-docx` para traduzir o conteúdo de um documento Word (.docx). Ele lê o texto de cada parágrafo, envia-o para a API do Azure para tradução e, em seguida, salva o conteúdo traduzido em um novo arquivo .docx.

---

## Funcionalidades

* Lê parágrafos de um arquivo .docx existente.
* Traduz o texto de cada parágrafo usando o serviço de tradução do Azure.
* Cria um novo documento .docx com o texto traduzido.
* Salva o arquivo traduzido com um novo nome, mantendo o original intacto.

---

## Como Usar

### Pré-requisitos
Certifique-se de ter o Python instalado. O script usa as bibliotecas `requests` e `python-docx`.

### Instalação

Abra o terminal e execute o seguinte comando para instalar as bibliotecas necessárias:

```bash
pip install requests python-docx
