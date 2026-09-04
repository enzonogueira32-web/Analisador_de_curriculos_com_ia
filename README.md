# Analisador de Currículos com IA

Sistema desenvolvido em Python para análise automatizada de currículos utilizando Inteligência Artificial. O projeto foi desenvolvido com integração planejada ao Google Gemini para realizar a análise dos currículos.

## Objetivo

O objetivo do projeto é facilitar a análise inicial de currículos, utilizando Inteligência Artificial para identificar informações relevantes, destacar pontos positivos e indicar possíveis melhorias.

A aplicação foi desenvolvida como um projeto de estudo e portfólio, demonstrando a utilização de Python, processamento de arquivos e integração com APIs de Inteligência Artificial.

## Funcionamento

O sistema segue o seguinte fluxo:

1. O usuário seleciona um currículo.
2. O sistema extrai o conteúdo do arquivo.
3. As informações são preparadas para análise.
4. O conteúdo pode ser enviado ao Google Gemini.
5. A Inteligência Artificial realiza a análise.
6. O resultado é apresentado ao usuário.

Fluxo da aplicação:

```text
Currículo
   ↓
Extração do conteúdo
   ↓
Python
   ↓
Google Gemini API
   ↓
Análise com IA
   ↓
Resultado
```

## Inteligência Artificial

O projeto foi desenvolvido para utilizar o **Google Gemini** como modelo de Inteligência Artificial responsável pela análise dos currículos.

A integração com a API foi implementada no código, porém **atualmente não possuo uma chave de API do Google Gemini configurada para o projeto**.

Por esse motivo, a funcionalidade de análise por IA depende da configuração de uma chave própria pelo usuário.

A IA foi planejada para analisar aspectos como:

* Experiência profissional
* Formação acadêmica
* Competências
* Cursos e certificações
* Organização das informações
* Pontos positivos
* Possíveis melhorias
* Adequação do currículo ao perfil apresentado

Os resultados gerados por Inteligência Artificial não devem ser considerados uma avaliação profissional definitiva.

## Tecnologias utilizadas

### Python

Principal linguagem utilizada no desenvolvimento da aplicação.

### Google Gemini

Modelo de Inteligência Artificial planejado para realizar a interpretação e análise dos currículos.

### Google GenAI

Biblioteca utilizada para realizar a comunicação entre a aplicação Python e a API do Google Gemini.

### Tkinter / CustomTkinter

Utilizado para criação da interface gráfica da aplicação.

### Processamento de arquivos

Bibliotecas de Python utilizadas para extrair e processar o conteúdo dos currículos.

## Estrutura do projeto

```text
analisador_curriculos/
│
├── analisador.py
├── ia.py
├── README.md
└── outros arquivos do projeto
```

A estrutura pode variar de acordo com a versão do projeto.

## Instalação

Clone o repositório:

```bash
git clone URL_DO_REPOSITORIO
```

Entre na pasta:

```bash
cd analisador_curriculos
```

Instale as dependências:

```bash
pip install -r requirements.txt
```

Caso o arquivo `requirements.txt` não esteja disponível, instale as bibliotecas necessárias manualmente.

## Configuração da API

A integração com o Google Gemini utiliza uma chave de API.

**Importante:** este projeto atualmente **não possui uma chave de API própria configurada**. A chave não está incluída no código nem no repositório.

Para utilizar a integração com o Gemini, o usuário deverá criar sua própria chave e configurá-la como variável de ambiente.

No PowerShell:

```powershell
$env:GEMINI_API_KEY="SUA_CHAVE_AQUI"
```

Depois, execute a aplicação:

```bash
python analisador.py
```

A chave da API nunca deve ser publicada diretamente no GitHub ou inserida permanentemente no código-fonte.

## Status da integração com IA

| Funcionalidade                   | Status                                 |
| -------------------------------- | -------------------------------------- |
| Interface gráfica                | Implementada                           |
| Seleção de currículo             | Implementada                           |
| Processamento do currículo       | Implementado                           |
| Estrutura para integração com IA | Implementada                           |
| Integração com Google Gemini     | Preparada                              |
| Chave própria da API             | Não disponível atualmente              |
| Análise utilizando Gemini        | Depende da configuração de uma API Key |

## Limitações

O projeto possui algumas limitações:

* A análise por Inteligência Artificial depende da configuração de uma chave da API do Google Gemini.
* Atualmente, o projeto não possui uma chave de API própria.
* A análise depende da qualidade das informações presentes no currículo.
* A Inteligência Artificial pode interpretar determinadas informações de maneira incorreta.
* O sistema não substitui uma avaliação realizada por profissionais de recrutamento.
* Currículos com formatos ou estruturas incomuns podem apresentar dificuldades durante a extração do conteúdo.
* A utilização do Gemini depende da disponibilidade e dos limites da API.

## Possíveis melhorias

Algumas funcionalidades que podem ser adicionadas futuramente:

* Comparação entre currículo e descrição de uma vaga.
* Sistema de pontuação de compatibilidade.
* Identificação automática de palavras-chave.
* Sugestões de melhorias específicas para cada vaga.
* Geração de uma versão aprimorada do currículo.
* Suporte a mais formatos de arquivo.
* Histórico de currículos analisados.
* Exportação da análise para PDF.
* Interface mais avançada.
* Banco de dados para armazenamento das análises.
* Testes automatizados.
* Criação de uma versão executável `.exe`.

## Contexto do projeto

Este projeto foi desenvolvido com finalidade educacional e de portfólio, buscando demonstrar conhecimentos em:

* Desenvolvimento com Python
* Interfaces gráficas
* Manipulação e processamento de arquivos
* Integração com APIs
* Inteligência Artificial generativa
* Variáveis de ambiente
* Processamento de documentos
* Organização de projetos
* Desenvolvimento de aplicações desktop

## Autor

**Enzo Nogueira**

Projeto desenvolvido para fins educacionais e de portfólio.

## Licença

Este projeto pode ser utilizado para fins de estudo e aprendizado.
