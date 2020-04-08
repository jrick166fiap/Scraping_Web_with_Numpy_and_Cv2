# Scraping Web Sites with Numpy and Cv2
### A ideia inicial do projeto é buscar nos sites de jornais todos os links de notícias sobre o tema "X", e depois coletar em cada link dessas notícias suas imagens sobre o tema escolhido.
#### Site 1
![globo](https://user-images.githubusercontent.com/31735230/78743477-1aea1f00-7935-11ea-832e-83371138a50d.jpg)
#### Site 2
![uol](https://user-images.githubusercontent.com/31735230/78743517-3523fd00-7935-11ea-8019-0b98cacc2059.jpg)



## Pré-requisitos
- 1 - Ambiente Windows, Linux ou Mac(Python(Core) ou Anaconda)

## Funcionamento básico do projeto
- 1 - Estrutura de pastas Coletando - Jornais > Jornalx > site.txt - Onde vai conter o link do site do jornal
- 2 - Estrutura de pastas Resultado - Jornais > Jornalx > catalogo_resultado_dia-mês-ano_hora.csv(Catalogo com sites e links)
- 3 - Estrutura de pastas Resultado Imagens > Jornalx  >Jornalx > Images > *.png(Resultados de todas as imagens localizadas do site Jornal)
- 4 - Estrutura de pastas Resultado Imagens > Jornalx  >Jornalx > final.JPG - resultado de toda concatenação das imagens do passo 3)

## Testando o projeto
#### Utlizando o Jupyter Notebook
Abrir o arquivo Crawler_with_Numpy_Cv2.ipynb e rode.


### Futuras implementações e melhorias:
- [ ] Um processo que rode de tempos em tempos realizando um novo sync dos dados(Cron+ Servidor Web) (Pendente)
- [ ] Refatoração da lógica (Pendente)
- [ ] Implementar conceito de filas com redis e RQ
