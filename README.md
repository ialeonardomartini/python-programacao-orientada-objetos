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
├── app.py                # Script principal: executa a lógica do menu e interações
├── modelos/
│   ├── restaurante.py    # Contém a classe Restaurante
│   └── avaliacao.py      # Contém a classe Avaliacao
└── README.md             # Este arquivo de documentação
```

- `restaurante.py`: classe `Restaurante`, com atributos como nome, categoria, ativo e avaliações, além dos métodos de comportamento.  
- `avaliacao.py`: classe `Avaliacao`, responsável por representar e validar as notas dos restaurantes.  
- `app.py`: interface de linha de comando que permite interagir com o sistema.

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
venv\Scripts\activate      # Windows
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
