# 📊 Power BI Kiosk Viewer

Este projeto foi criado para exibir **dashboards do Power BI em loop
automático**, ideal para TVs corporativas, salas de operação e
monitoramento em tempo real.

Ele garante uma experiência limpa, sem recarregamentos desnecessários, e
com atualização periódica para manter os dados sempre frescos.

------------------------------------------------------------------------

## ✨ Funcionalidades

-   ✅ **Pré-carregamento dos dashboards** em iframes\
-   ✅ **Alternância suave** entre os relatórios, sem reload a cada
    troca\
-   ✅ **Atualização automática a cada 30 minutos** (sem afetar a
    experiência de visualização)\
-   ✅ **Loop contínuo** entre várias páginas do Power BI\
-   ✅ **Remoção da barra inferior padrão do Microsoft**, deixando o
    painel limpo e profissional

------------------------------------------------------------------------

## 🚀 Como usar

1.  **Clone o repositório** ou baixe os arquivos:

    ``` bash
    git clone https://github.com/pedrosenna1/Kiosk_PBI.git
    ```

2.  **Edite o arquivo `index.html`**:

    -   Localize a variável `urls` no início do `<script>`.

    -   Substitua pelos links de visualização do Power BI que você
        deseja exibir:

        ``` javascript
        const urls = [
          "https://app.powerbi.com/view?r=SEU_LINK_AQUI",
          "https://app.powerbi.com/view?r=OUTRO_LINK_AQUI"
        ];
        ```

3.  **Abra o arquivo `PowerBiTvTool.html`** no navegador ou hospede em um
    servidor web.

    -   Pode ser hospedado em qualquer ambiente simples (ex.: Apache,
        NGINX, GitHub Pages, Vercel).

------------------------------------------------------------------------

## ⚙️ Configurações

-   ⏱️ O tempo entre trocas é configurado pelo seletor na própria tela
    (5s, 10s, 1min, etc).\
-   🔄 O refresh automático de cada relatório acontece a cada **30
    minutos** (pode ser alterado na constante `refreshEachMs` no
    JavaScript).\
-   🎨 Os efeitos de transição podem ser trocados via seletor de efeitos
    na tela.

------------------------------------------------------------------------

## 🖥️ Exemplos de uso

-   TVs em áreas comuns mostrando KPIs da empresa\
-   Salas de operação exibindo indicadores em tempo real\
-   Eventos e apresentações com dashboards dinâmicos

------------------------------------------------------------------------







------------------------------------------------------------------------

💡 Desenvolvido para facilitar a vida de quem precisa exibir
**dashboards do Power BI de forma contínua e profissional**.
