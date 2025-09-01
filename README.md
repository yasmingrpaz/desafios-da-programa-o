# desafios-da-programa-o
{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": []
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "markdown",
      "source": [
        "## Aula 1"
      ],
      "metadata": {
        "id": "oWwIJdTn3hUW"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "print(\"I Competição de Programação da Start\")"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "As7u4tl6vASU",
        "outputId": "1f85debe-4ab6-433e-e49d-88122e1c34d0"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "I Competição de Programação da Start\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "ano = \"II\"\n",
        "\n",
        "print(ano, \"Competição de Programação da Start\")"
      ],{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": []
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "markdown",
      "source": [
        "## Aula 1"
      ],
      "metadata": {
        "id": "oWwIJdTn3hUW"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "print(\"I Competição de Programação da Start\")"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "As7u4tl6vASU",
        "outputId": "1f85debe-4ab6-433e-e49d-88122e1c34d0"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "I Competição de Programação da Start\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "ano = \"II\"\n",
        "\n",
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "-kLPKftcxTAl",
        "outputId": "7a51392d-a057-4a8f-d9dc-7605bc5c7f8d"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "II Competição de Programação da Start\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "print(f\"{ano} Competição de Programação da Start\")"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "WLUAVjl4xvuW",
        "outputId": "ef030785-6a16-4fdb-80d5-b6cc267ef6ff"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "II Competição de Programação da Start\n"
          ]
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "## Aula 2"
      ],
      "metadata": {
        "id": "f1KsTmx03lxi"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "Contexto:\n",
        "\n",
        "Uma escola está promovendo uma campanha de incentivo à leitura, em que cada estudante recebe pontos ao concluir livros. Esses pontos podem ser trocados por diferentes premios da escola. As categorias de livros têm valores de pontos diferentes:\n",
        "\n",
        "* Livro de ficção: 10 pontos\n",
        "* Livro de não-ficção: 8 pontos\n",
        "* Livro infantil: 6 pontos\n",
        "\n",
        "**Problema:**\n",
        "\n",
        "Rodrigo leu um livro de cada categoria. Agora ele quer saber quantos pontos acumulou com sua leitura.\n",
        "\n",
        "Nosso objetivo é criar um programa em Python que:\n",
        "\n",
        "* Armazene a pontuação de cada categoria de livro em uma variável.\n",
        "* Calcule o total de pontos acumulados por Rodrigo.\n",
        "* Mostre na tela o total de pontos acumulados por Rodrigo."
      ],
      "metadata": {
        "id": "UiUmhq023phx"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "livro_ficcao = 10\n",
        "livro_nficcao = 8\n",
        "livro_infantil = 6\n",
        "\n",
        "pontos_rodrigo = livro_ficcao + livro_nficcao + livro_infantil\n",
        "\n",
        "print(f\"Os pontos totais do Rodrigo são: {pontos_rodrigo}\")"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "GQRpxCIk4B_O",
        "outputId": "cad1f838-f515-4a70-9cc5-ef516de4b45c"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Os pontos totais do Rodrigo são: 24\n"
          ]
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "### Desafio\n",
        "\n",
        "Ana também participou da campanha e leu 2 livros de ficção e 5 livros infantis.\n",
        "\n",
        "Como podemos calcular o total de pontos de Ana? Será que é possível calcular o total de pontos acumulados por Rodrigo e Ana juntos?"
      ],
      "metadata": {
        "id": "SwK66FFS44_1"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "## Aula 3\n"
      ],
      "metadata": {
        "id": "EDZC6pjHbhA8"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "Divisão do tesouro: https://olimpiada.ic.unicamp.br/passadas/OBI2020/fase1/programacao-b/\n",
        "\n",
        "A turma do 2º ano encontrou um envelope cheio de figurinhas. Para garantir uma divisão justa, todos concordaram com a sugestão de João, o dono do envelope:\n",
        "\n",
        "Cada amigo, exceto João, deve receber exatamente o mesmo número de figurinhas. João deve receber o dobro da quantidade que cada amigo recebe. Pode ser que o fato de João ser o dono do envelope tenha ajudado a convencer os amigos, mas também contribuiu o fato de que, do jeito proposto, a divisão era exata, sem sobrar nem faltar figurinhas.\n",
        "\n",
        "**Problema:**\n",
        "\n",
        "Crie um programa que determine a quantidade de figurinhas que João recebeu, dado o número total de figurinhas no envelope e o número de amigos de João.\n",
        "\n",
        "**Entrada:**\n",
        "\n",
        "* A primeira linha contém um número inteiro `total_figurinhas`, que representa o número de figurinhas no envelope.\n",
        "* A segunda linha contém um número inteiro `numero_amigos`, que representa a quantidade de amigos de João (excluindo o próprio João)."
      ],
      "metadata": {
        "id": "Yd3mUA12bj7g"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "total_figurinhas = int(input(\"Digite o total de figurinhas: \"))\n",
        "numero_amigos = int(input(\"Digite o número de amigos: \"))\n",
        "\n",
        "figurinhas_amigos = total_figurinhas // (numero_amigos + 2)\n",
        "\n",
        "figurinhas_joao = 2 * figurinhas_amigos\n",
        "\n",
        "print(f\"João recebeu {figurinhas_joao} figurinhas.\")\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "aL5npKxJheU8",
        "outputId": "e7f06a60-c5d3-4f45-b4ad-79978f6973c5"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Digite o total de figurinhas: 100\n",
            "Digite o número de amigos: 5\n",
            "João recebeu 28 figurinhas.\n"
          ]
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "### Desafio\n",
        "\n",
        "Depois de dividir as figurinhas no recreio, João percebeu que ainda havia algumas figurinhas extras em sua mochila. Ele decidiu que essas figurinhas extras também devem ser distribuídas de forma justa entre ele e seus amigos, mantendo a mesma regra:\n",
        "\n",
        "Cada amigo recebe uma quantidade igual de figurinhas.\n",
        "João recebe o dobro da quantidade de figurinhas que cada amigo recebe.\n",
        "Ajude João a distribuir todas as figurinhas, incluindo as extras, de maneira justa, sem deixar nenhuma figurinha sobrando.\n",
        "\n",
        "Entrada\n",
        "\n",
        "* número total de figurinhas no envelope.\n",
        "* número de amigos de João (excluindo o próprio João).\n",
        "* número de figurinhas extras encontradas na mochila de João.\n",
        "* calcular a nova quantidade total de figurinhas, somando as extras.\n",
        "* dividir as figurinhas entre João e seus amigos, garantindo que João receba o dobro de figurinhas que cada amigo.\n",
        "exibir a quantidade de figurinhas que João recebeu."
      ],
      "metadata": {
        "id": "SPWpMScwjCrj"
      }
    }
  ]
}
