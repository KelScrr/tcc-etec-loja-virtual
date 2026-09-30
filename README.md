# Loja virtual · TCC da ETEC

Trabalho de Conclusão de Curso do **Ensino Médio Técnico em Desenvolvimento de Sistemas** da **ETEC Parque da Juventude** (2023).

É um site para uma loja de roupas, com front-end, back-end e banco de dados feitos do zero. A loja mostra os produtos numa vitrine separada por categoria, e a administração cadastra, edita e exclui produtos.

![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

## Funcionalidades

- Página inicial com banners e atalhos para as categorias
- **Vitrine por categoria:** blusas e tops, vestidos, saias, calças e shorts, conjuntos e acessórios
- Preço e parcelamento de cada produto
- **Área administrativa:** cadastro de produtos com foto, edição e exclusão
- Telas de login e de cadastro da cliente
- Página "Sobre nós"

## Estrutura

```
├── página_inicial/            # Home com banners e categorias
├── Vitrine/                   # Vitrine geral e uma página por categoria (PHP + MySQL)
├── Produtos - Adicionar/      # Cadastro de produtos
├── Produtos - Editar_Excluir/ # Edição e exclusão (excluir.php) e fotos enviadas
├── Login/                     # Login da cliente
├── login_botões/              # Tela de escolha entre entrar e cadastrar
├── Sobre nós/                 # Sobre a loja
└── bdtcc.sql                  # Script do banco de dados (tabela vitrine)
```

## Como rodar

1. Instale o [XAMPP](https://www.apachefriends.org/) (Apache + MySQL).
2. Copie esta pasta para `htdocs`.
3. No phpMyAdmin, crie o banco `vitrine` e importe o `bdtcc.sql`.
4. Acesse `http://localhost/<nome-da-pasta>/página_inicial/` no navegador.

A conexão usa o usuário `root` sem senha, que é o padrão do XAMPP local.
