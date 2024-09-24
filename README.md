# Desafio Java Músicas Preferidas

Projeto implementado durante curso Alura posto como desafio.
Aplicação cadastra músicas e podcasts preferidos, com classes utilizando os conceitos de orientação a objetos: abstração, herança, encapsulamento e polimorfismo.

## 🎶🎧 Projeto Músicas Preferidas

- Classe **Audio** com os atributos (titulo, totalReproducoes, totalCurtidas e classificacao).
- Utiliza encapsulamento, atributos privados e *getters* e *setters* para acessar e modificar os atributos.
- Métodos curte() e reproduz(), que incrementa as variáveis totalCurtidas e totalReproducoes, respectivamente.
- Código em pacotes.
- Classe **Musica** estendendo de Audio, com os atributos adicionais **album**, **cantor** e **genero**.
- Classe **Podcast** estendendo de Audio, com os atributos adicionais **apresentador** e **descricao**.
- Classe Principal com objeto do tipo Musica e outro do tipo Podcast, preenchendo seus atributos;
- Loop para chamar os métodos curte() e reproduz() a fim de simular um número grande de reproduções e curtidas.
- Sobrescrita do método *getClassificacao* na classe Musica, definindo que se a mesma tiver mais de 2000 **reproduções** a classificação será 10 e para valores inferiores a classificação será 8.
- Sobrescrita do método *getClassificacao* na classe Podcast, definindo que se o mesmo tiver mais de 500 **curtidas** a classificação será 10 e para valores inferiores, a classificação será 7.
- Classe **MusicasPreferidas** com um método sem retorno (void) chamado *inclui*, que receberá como parâmetro um Audio.
- O *getClassificacao* exibi mensagem. Para classificação igual ou superior a 9, imprimi no terminal uma mensagem e se for inferior, imprimi uma outra mensagem.

<p></p>

Exemplo de mensagem exiba para classificação superio e inferior a 9.

<p></p>

![java-desafio-alura2](https://github.com/user-attachments/assets/377e1a4c-3c37-4600-aeda-a892fc078a37)
