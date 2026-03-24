# 🚀 Nave Orion — Algoritmo de Segurança

Algoritmo de verificação de segurança para a Nave Orion, desenvolvido como atividade integradora da FIAP.

## 📋 Sobre o Projeto

Este projeto implementa um algoritmo de verificação de segurança que simula as checagens necessárias antes da decolagem da Nave Orion. O sistema verifica parâmetros como temperatura, pressão dos tanques, integridade estrutural e energia, calculando ao final a autonomia energética da nave.

## 🔍 Parâmetros Verificados

| Parâmetro | Faixa Segura |
|---|---|
| Temperatura interna da cabine | 18°C a 26°C |
| Temperatura externa da nave | 0°C a 2760°C |
| Pressão dos tanques de propelente | 20 a 30 bars |
| Pressão dos tanques de gás (Hélio/O²/N²) | 350 a 420 bars |
| Energia solar gerada | 9 a 11.2 kW |
| Armazenamento das baterias | 12 a 14.4 kWh |
| Carga das baterias | 94% a 97% |
| Integridade estrutural (CM, ESM, LAS, OSA) | 1 = OK / 0 = Falha |

## ▶️ Como Executar

1. Acesse o notebook pelo Google Colab:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1k9geij84sCA6iqYNTvgjnkhk93bbXIbB#scrollTo=a5W9kGQ5Mn-E)


2. Execute todas as células em ordem
3. Insira os dados quando solicitado
4. Caso o dado inserido esteja fora da faixa segura o algoritmo encerra e aparece a mensagem de "Abordando decolagem"

## 🖥️ Exemplo de Execução
```
Bem vindos ao algoritmo de segurança da Nave Orion!
Qual é o seu nome astronauta? Victor Gonçalves Mantovani
Victor Gonçalves Mantovani, está preparado para a verificação? S/N Sim
Iniciando verificação de segurança...
...
Verificação estrutural finalizada, nave liberada para decolagem!
A nave tem 1h e 20min de autonomia energética!
```

## 🛠️ Tecnologias Utilizadas

- Python 3
- Google Colab (Jupyter Notebook)

## 👨‍🚀 Autor

**Victor Gonçalves Mantovani**  
FIAP — Ciências da Computação
