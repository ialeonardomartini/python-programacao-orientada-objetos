# 🍽️ Python - Programação Orientada a Objetos

Este repositório contém o projeto desenvolvido durante o curso [**Python: aplicando a Orientação a Objetos**](https://cursos.alura.com.br/course/python-aplicando-orientacao-objetos) da Alura. O objetivo foi praticar os principais conceitos de **Programação Orientada a Objetos (POO)** com Python, aplicando-os em um sistema de cardápio digital.

## 📌 Sobre o Projeto

O projeto simula um cardápio que:

- Cadastra restaurantes com nome e categoria  
- Controla o status de ativação (ativo/inativo)  
- Registra avaliações dos restaurantes  
- Lista todos os restaurantes cadastrados com suas informações  

Esse sistema é totalmente orientado a objetos, com foco em escrita de código limpo, reutilizável e fácil de manter.

## 📚 Conceitos Aplicados

Durante o curso e o desenvolvimento do projeto, os seguintes pilares e práticas da POO foram trabalhados:

- Definição de classes e objetos  
- Construtores (`__init__`)  
- Atributos de instância e de classe  
- Métodos públicos e privados  
- Encapsulamento com `@property` e setters  
- Métodos de classe e métodos estáticos  
- `List comprehension` com objetos  
- Dunder methods (como `__str__`)  

## 🧱 Estrutura do Projeto

```text
python-programacao-orientada-objetos/
├── app.py                      # Script principal: executa a lógica do menu e interações
├── modelos/
│   ├── __init__.py             # Arquivo vazio que define o pacote
│   ├── avaliacao.py            # Contém a classe Avaliacao
│   ├── restaurante.py          # Contém a classe Restaurante
│   └── cardapio/
│       ├── __init__.py         # Arquivo vazio que define o subpacote
│       ├── item_cardapio.py    # Classe base para itens de cardápio
│       ├── prato.py            # Define a classe Prato (herda de ItemCardapio)
│       └── bebida.py           # Define a classe Bebida (herda de ItemCardapio)
└── README.md                   # Este arquivo de documentação
```

- `restaurante.py`: define a classe `Restaurante`, com atributos como nome, categoria, status e avaliações.  
- `avaliacao.py`: define a classe `Avaliacao`, que representa e valida as notas atribuídas.  
- `item_cardapio.py`: classe base para os itens do cardápio, como pratos e bebidas.  
- `prato.py` e `bebida.py`: subclasses de `ItemCardapio` que representam pratos e bebidas, respectivamente.  
- `__init__.py`: arquivos vazios usados para indicar que as pastas são pacotes Python válidos.

## ▶️ Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/ialeonardomartini/python-programacao-orientada-objetos.git
cd python-programacao-orientada-objetos
```

2. (Opcional) Crie um ambiente virtual:

```bash
python -m venv venv
source venv/bin/activate     # Linux/macOS
venv\Scriptsctivate        # Windows
```

3. Execute o programa:

```bash
python app.py
```

## ✅ Funcionalidades Disponíveis

- **Cadastrar restaurante**: informe o nome e a categoria  
- **Listar restaurantes**: exibe nome, categoria, média de avaliações e status  
- **Avaliar restaurante**: registra uma nova nota de avaliação  
- **Alternar status**: ativa ou desativa o restaurante  

## 📎 Link do Curso

Este projeto foi desenvolvido com base no curso da Alura:  
[Python: aplicando a Orientação a Objetos](https://cursos.alura.com.br/course/python-aplicando-orientacao-objetos)

## 📝 Licença

Este projeto está sob a licença MIT. Consulte o arquivo `LICENSE` para mais informações.

## 🙋‍♂️ Autor

Desenvolvido por [@ialeonardomartini](https://github.com/ialeonardomartini) 🚀
