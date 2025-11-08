# Investigando Filmes dos Anos 1990 🎬

🇺🇸 Check out the English version here: https://github.com/devleticiastahl/90smovies-netflix/blob/main/README.en-us.md

## Sobre o projeto

Este projeto analisa os dados de filmes dos anos 1990 da Netflix para descobrir tendências de entretenimento, gêneros populares e insights chave dessa década influente no cinema. Baseada no conjunto de dados `netflix_data.csv`, a análise oferece recomendações para empresas de produção que buscam criar filmes nostálgicos.

### 🛠️ Ferramentas
- Jupyter notebook
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Figma

## Análise

### 1. Número de Filmes Lançados
Os lançamentos de filmes de 1990 a 1999 mostraram uma tendência constante de aumento, com um crescimento significativo entre 1996 e 1997.

<img src="https://drive.google.com/uc?id=1EWzXvVPdFjWufq8jqnpQPFD1q6eVB-vu" alt="Número de Filmes Lançados por País- TOP3" width="700" style=""/>

Esse aumento pode ser devido a diversos fatores, como avanços na tecnologia cinematográfica, mudanças nas preferências do público ou maior capacidade de produção. A análise das contribuições de diferentes países mostra os **EUA** como o principal player, enquanto a **Índia** demonstrou um crescimento significativo na produção.

<img src="https://drive.google.com/uc?id=10IA4NEvoIglqVAEkA5NyR9SwbeTuMHsk" alt="Número de Filmes Lançados por País- TOP3" width="700" style=""/>

- **EUA**: Líder em lançamentos de filmes com um pico em 1997.
- **Índia**: Crescimento consistente no final dos anos 1990, refletindo o surgimento de Bollywood.
- **Reino Unido**: Aumento notável, mas com produção menor em comparação aos EUA e Índia.

### 2. Gêneros Populares dos Anos 90
Os gêneros mais populares dos anos 1990 foram **Ação**, **Drama** e **Comédia**, refletindo a demanda do público por aventuras emocionantes, narrativas emocionais e humor. **Filmes Infantis** e **Clássicos** também foram populares, atraindo famílias e aqueles em busca de entretenimento atemporal.

<img src="https://drive.google.com/uc?id=1GYsQgOASpCcFst8gBjuggTiqwz7x64Lb" alt="Gêneros Populares dos Anos 90" width="700" style=""/>

Analisando os três principais países produtores de filmes, observamos que na **Índia**, os **Dramas** são os mais populares. Nos **EUA** e **Reino Unido**, a diversidade de gêneros é mais ampla, com destaque para Ação, Comédia e Drama.

<img src="https://drive.google.com/uc?id=11pBDKWGHDMLV3RPl_nMMOxeoBZVYbgYX" alt="Gêneros Populares dos Anos 90 por País" width="700" style=""/>

### 3. Diretores dos Anos 90
A maioria dos diretores nos anos 90 lançou entre 1 e 4 filmes, com uma média de **1,24 filmes por diretor**. Não houve grandes figuras dominantes da década.

#### Top 10 Diretores por Número de Filmes Lançados

```python
top_directors = movies_90s['director'].value_counts().head(10)
top_directors
```

| **Diretor**            | **Número de Filmes** |
| ---------------------- | -------------------- |
| Johnnie To             | 4                    |
| Youssef Chahine        | 3                    |
| Umesh Mehra            | 3                    |
| Gregory Hoblit         | 3                    |
| Subhash Ghai           | 3                    |
| Mahesh Bhatt           | 3                    |
| Rajkumar Santoshi      | 3                    |
| Sooraj R. Barjatya     | 3                    |
| David Dhawan           | 2                    |
| Quentin Tarantino      | 2                    |

## 4. Temas Principais

A década de 1990 trouxe uma rica variedade de temas, como **"Love"**, **"beauty"**, **"romance"**, e temas de **"danger"**, **"mystery"**, **"fear"**, refletindo uma grande diversidade de interesses cinematográficos.

<img src="https://drive.google.com/uc?id=1LTq4Rn1jJ6M3g0ngtFfq5zwJRQ6xGBHt" alt="Word Cloud Título dos Filmes" width="700" style=""/>

Os temas de **família** e **amadurecimento**, além dos **filmes de ação** e **aventura**, dominaram o cinema dos anos 90, com forte apelo emocional e envolvimento com o público.

<img src="https://drive.google.com/uc?id=1BSXOuAfq55FLY7eA0IFGJCq76x9Ymmn2" alt="Word Cloud Descrição dos Filmes" width="700" style=""/>

## 5. Duração dos Filmes

A duração típica dos filmes variava de **100 a 120 minutos**, com uma média de **115 minutos**.

<img src="https://drive.google.com/uc?id=1_xTM9gr2Shi_0sNxHO5ZCLm7btNGQ1cV" alt="Distribuição da Duração dos Filmes" width="700" style=""/>

Os **filmes de ação** e **dramas** tendem a ser mais longos, enquanto **comédias** e **filmes familiares** são mais curtos.

<img src="https://drive.google.com/uc?id=1Gm2XxTHsRqIBM22Jl1jT7Nyv79T3SMp3" alt="Análise da Duração dos Filmes" width="700" style=""/>

## Conclusão

### Principais Recomendações para Criar Filmes Nostálgicos dos Anos 90

- **Gêneros Dominantes**: Foque em **Ação**, **Drama** e **Comédia** para evocar a essência cinematográfica dos anos 90.
- **Temas Universais**: Incorpore temas como **Romance**, **Família**, **Perigo** e **Aventura**, que foram populares na década.
- **Diretores e Estilo**: Inspire-se em diretores como **Quentin Tarantino** e **Johnnie To** para técnicas de narrativa.
- **Duração dos Filmes**: Mantenha a duração entre **100-120 minutos** para capturar o ritmo dos filmes da época.
- **Influências Regionais**: Combine elementos do estilo de Hollywood com o drama emocional de Bollywood.
- **Personagens Atemporais**: Crie **heróis ousados** e **figuras relacionáveis** para fortalecer o apelo emocional.
- **Nostalgia e Técnica Moderna**: Misture a estética dos anos 90 com narrativas contemporâneas para atrair o público atual.

## Contribuições

☕ **Contribuições são bem-vindas!**




