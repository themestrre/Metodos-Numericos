<img src="Figuras/logo_unb.jpg" alt="descrição da figura" width="400"/>

# MÉTODOS NUMÉRICOS EM CIÊNCIAS MECÂNICAS

**Aluno:** Carlos Eduardo Leite de Oliveira

**Professor:** Dr. Rafael Gabler Gontijo 

Universidade de Brasília - Departamento de Engenharia Mecânica

Grupo Vortex - Mecânica dos Fluidos de Escoamentos Complexos

Repositório destinado ao armazenamento e descrição dos códigos desenvolvidos para as atividades da disciplina de Métodos Numéricos em Ciências Mecânicas.

Os códigos apresentados nesse repositório são todos feitos em linguagem de programação Python, onde foi escolhido o Google Colab que é um ambiente de notebooks Jupyter baseado na nuvem que permite ao usuário: 

- Escrever e executar código Python diretamente no navegador; 
- Usar GPUs e TPUs gratuitamente para tarefas computacionais intensivas; 
- Compartilhar e colaborar em tempo real, como em um Google Docs;
- Acessar bibliotecas como NumPy, pandas, Matplotlib, TensorFlow, etc., sem instalação local.

Para utilizar o Google Colab, basta acessar o site https://colab.research.google.com e fazer login com sua conta do Google. Com isso, é possível criar notebooks para cada atividade, desenvolver os códigos e executá-los em qualquer máquina com acesso à internet.

## Código 1 - Sedimentação de uma esfera em um fluido viscoso

### Teoria
O código apresentado tem por objetivo a resolução de sedimentação de uma esfera em um fluido viscoso onde será aplicado o Método de Runge-Kutta de 4a ordem. Como é apresentado no esquematico da Figura 1.

<p align="center">
  <img src="Figuras/Fig1.png" alt="Minha Figura" width="400"/>
  <br>
  <em>Figura 1: Esquemático do problema de sedimentação.</em>
</p>

Para esse problema é considerando a força de arrasto, empuxo e peso. A segunda lei de Newton aplicada a este problema é:

$$
m_p \frac{dv_z}{dt} = -6 \pi \eta a v_z - \frac{9}{4} \pi \rho_r a^2 v_z^2 + \frac{4}{3} \pi a^3 \Delta \rho g
$$

Na sua forma adimensional é:

$$
\mathrm{St} \frac{d v_{z}^{\ast}}{d t^{\ast}} = 1 - v_{z}^{\ast}
$$

A solução exata é dada por:

$$
v_{z}^{\ast}(t) = 1 - e^{-t/\mathrm{St}}
$$

### Resultados

## Código 2 - 

## Código 3 - 

## Código 4 - 

## Código 5 - 

