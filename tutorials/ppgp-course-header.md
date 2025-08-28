# Cabeçalhos de Disciplinas

**Com o modo de edição ativo**, vá até a primeira seção da sua disciplina (**Geral**) e clique nos *três pontinhos* e depois em `Editar seção`.

![Figura 1](../assets/ppgp-course-header/1.png)

Na próxima tela, na seção Sumário, clique na seta para baixo, como indicado na figura a seguir.

![Figura 2](../assets/ppgp-course-header/2.png)

Em seguida, clique no símbolo `</>` para ativar o modo **editor HTML**. Você vai notar que o aparente texto em branco vai se tornar algo parecido com o demonstrado na figura a seguir.

![Figura 3](../assets/ppgp-course-header/3.png)

Apague todo o texto contido nesta caixa e substitua pelo trecho de código a seguir:

```html
<div class="ppgp-disciplina-title">
    <h1>Nome da disciplina aqui</h1>
</div>
<div class="ppgp-recursos mt-3">
    <a href="#section-9">Período Presencial</a>
</div>

<div class="ppgp-quinzenas">
    <a href="#section-1">
        <span>1ª quinzena</span>
        <p>de XX/XX a XX/XX</p>
    </a>
    <a href="#section-2">
        <span>2ª quinzena</span>
        <p>de XX/XX a XX/XX</p>
    </a>
    <a href="#section-3">
        <span>3ª quinzena</span>
        <p>de XX/XX a XX/XX</p>
    </a>
    <a href="#section-4">
        <span>4ª quinzena</span>
        <p>de XX/XX a XX/XX</p>
    </a>
    <a href="#section-5">
        <span>5ª quinzena</span>
        <p>de XX/XX a XX/XX</p>
    </a>
    <a href="#section-6">
        <span>6ª quinzena</span>
        <p>de XX/XX a XX/XX</p>
    </a>
    <a href="#section-7">
        <span>7ª quinzena</span>
        <p>de XX/XX a XX/XX</p>
    </a>
    <a href="#section-8">
        <span>8ª quinzena</span>
        <p>de XX/XX a XX/XX</p>
    </a>
</div>
<div class="text-center">
    <a href="#section-10">Recuperação/Atestado Médico</a>
</div>
```

Você pode substituir todo o conteúdo entre as duas *tags* `h1` e escrever ali o nome da disciplina que está configurando. Ou, caso não sinta segurança em escrever nessa tela, você pode clicar novamente em `</>`, no painel superior, e retornar para o modo clássico de edição.

Você vai perceber que o layout da primeira tela terá se ajustado à identidade visual do PPGP.

![Figura 4](../assets/ppgp-course-header/4.png)

Você pode editar à vontade o nome da sua disciplina nessa tela, sem precisar olhar mais para a edição em HTML.

Ajuste também as datas iniciais e finais de cada quinzena.

Feito isso, basta clicar em `Salvar mudanças` e o cabeçalho da sua disciplina estará publicado.

## Organização dos tópicos

Para que este recurso funcione com eficácia, os tópicos da disciplina **devem** ser cadastrados na seguinte ordem:

- Geral
- 1ª quinzena
- 2ª quinzena
- 3ª quinzena
- 4ª quinzena
- 5ª quinzena
- 6ª quinzena
- 7ª quinzena
- 8ª quinzena
- Recuperação/Atestado Médico

Após o último, sinta-se livre para adicionar quantos mais achar necessário.