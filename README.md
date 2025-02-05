# Investigando Filmes dos Anos 1990

## Sobre o projeto

Este projeto analisa os dados de filmes dos anos 1990 da Netflix para descobrir tendências de entretenimento, gêneros populares e insights chave dessa década influente no cinema. Baseada no conjunto de dados `netflix_data.csv`, a análise oferece recomendações para empresas de produção que buscam criar filmes nostálgicos.

### 🛠️ Ferramentas
- Datalab notebook
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Figma

![Mobile-Cover.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/7c131856-cc00-41a8-94ec-fef908541624/a2c985df-1148-48d6-8f9c-c1db234f6cd0/Mobile-Cover.png)

## Análise

### 1. Número de Filmes Lançados
Os lançamentos de filmes de 1990 a 1999 mostraram uma tendência constante de aumento, com um crescimento significativo entre 1996 e 1997.

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/7c131856-cc00-41a8-94ec-fef908541624/7e4dfa04-4065-454a-ad76-8e998cebb6fe/image.png)

Esse aumento pode ser devido a diversos fatores, como avanços na tecnologia cinematográfica, mudanças nas preferências do público ou maior capacidade de produção. A análise das contribuições de diferentes países mostra os **EUA** como o principal player, enquanto a **Índia** demonstrou um crescimento significativo na produção.

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/7c131856-cc00-41a8-94ec-fef908541624/df90103d-2326-4a44-927c-ad39dd3f7a8f/image.png)

- 🇺🇸 **EUA**: Líder em lançamentos de filmes com um pico em 1997.
- 🇮🇳 **Índia**: Crescimento consistente no final dos anos 1990, refletindo o surgimento de Bollywood.
- 🇬🇧 **Reino Unido**: Aumento notável, mas com produção menor em comparação aos EUA e Índia.

### 2. Gêneros Populares dos Anos 90
Os gêneros mais populares dos anos 1990 foram **Ação**, **Drama** e **Comédia**, refletindo a demanda do público por aventuras emocionantes, narrativas emocionais e humor. **Filmes Infantis** e **Clássicos** também foram populares, atraindo famílias e aqueles em busca de entretenimento atemporal.

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/7c131856-cc00-41a8-94ec-fef908541624/adebbf80-b677-4c0e-82da-b1713eff68a6/image.png)

Analisando os três principais países produtores de filmes, observamos que na **Índia**, os **Dramas** são os mais populares. Nos **EUA** e **Reino Unido**, a diversidade de gêneros é mais ampla, com destaque para Ação, Comédia e Drama.

### 3. Diretores dos Anos 90
A maioria dos diretores nos anos 90 lançou entre 1 e 4 filmes, com uma média de 1,24 filmes por diretor. Não houve grandes figuras dominantes da década.

#### Top 10 Diretores por Número de Filmes Lançados

```python
top_directors = movies_90s['director'].value_counts().head(10)
top_directors
