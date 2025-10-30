## Imagens Dinâmicas

[Imagens Dinâmicas – @Curso em Vídeo HTML5 e CSS3](https://youtu.be/XXXXXXX)  <!-- Substitua pelo link correto do vídeo -->

### O que aprendi?

- Aprendi que **imagens dinâmicas** são aquelas que **mudam automaticamente conforme o tamanho da tela** ou dispositivo.  
- Para criar imagens dinâmicas, utiliza-se a tag `<picture>`, que permite definir **diferentes arquivos de imagem** com base em condições específicas.  
- Dentro de `<picture>`, usamos várias tags `<source>` com o atributo `media` para definir **larguras máximas** ou **mínimas**:  
  - Exemplo:  
    ```html
    <picture>
      <source media="(max-width: 750px)" srcset="imagem-pequena.png" type="image/png">
      <source media="(max-width: 1050px)" srcset="imagem-media.png" type="image/png">
      <img src="imagem-grande.png" alt="Imagem flexível">
    </picture>
    ```
- Entendi que o navegador escolhe automaticamente **a melhor imagem** de acordo com o tamanho da tela (celular, tablet ou PC).  
- O professor explicou que essa técnica melhora o **desempenho do site**, pois evita carregar imagens grandes em dispositivos pequenos.  
- Aprendi que o atributo `alt` continua sendo essencial para **acessibilidade e SEO**.  
- Compreendi que imagens dinâmicas são muito úteis em **sites responsivos**, garantindo uma boa **experiência visual** em todos os dispositivos.

