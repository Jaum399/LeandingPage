
# Landing Page com carrossel e integração de formulários

Este repositório contém o código-fonte para uma landing page responsiva que promove um curso introdutório de tecnologia pela DNC School. A página apresenta seções dinâmicas, incluindo um carrossel para depoimentos, um vídeo incorporado e um formulário de inscrição para registro do curso.

## Recursos

### Seção de cabeçalho
- Exibe o logotipo da DNC School.
- Inclui um título de chamada para ação e uma breve descrição do curso.

### Seção de informações
- Destaca os principais benefícios do curso:
- **Certificado de conclusão**
- **4 horas de conteúdo**
- **Aulas gravadas on-line**

### Seção de vídeo
- Incorpora um vídeo do YouTube apresentando o curso e seus benefícios.
- Acompanhado por um bloco de texto descritivo.

### Seção de carrossel
- Exibe depoimentos usando navegação interativa.
- **Lógica JavaScript**: As funções `RolarParaDireita` e `RolarEsquerda` alternam a visibilidade dos elementos do carrossel.

### Seção de formulário
- Um formulário de inscrição integrado com a **API SheetMonkey** para envio de dados.
- Campos de entrada:
- Nome
- E-mail
- Número de telefone
- Inclui um botão de envio estilizado para melhor experiência do usuário.

## Tecnologias usadas
- **HTML5**: Estrutura da página.
- **CSS3**: Estilo e layout responsivo.
- **JavaScript**: Funcionalidade interativa para o carrossel.
- **API SheetMonkey**: Lida com envios de formulário.

## Uso

### Visualização ao vivo
Para visualizar a demonstração ao vivo, implante o código em um servidor web ou use um ambiente de desenvolvimento local.

### Executar localmente
1. Clone o repositório:
```bash
git clone https://github.com/seu-nome-de-usuário/landing-page-carousel.git
```
2. Abra `index.html` no seu navegador preferido.
3. Certifique-se de que o `style.css` e todas as imagens referenciadas estejam nos diretórios corretos.

## Scripts
O código JavaScript fornece a lógica para o carrossel:
- **`RolarParaDireita`**: Oculta o primeiro depoimento e exibe o terceiro.
- **`RolarEsquerda`**: Restaura o primeiro depoimento enquanto oculta o terceiro.

## Contribuindo
Contribuições são bem-vindas! Sinta-se à vontade para bifurcar o repositório e enviar solicitações de pull para novos recursos ou correções de bugs.

## link 
https://leandingpageschool.netlify.app/
