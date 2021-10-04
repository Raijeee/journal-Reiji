{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "name": "Untitled1.ipynb",
      "provenance": [],
      "authorship_tag": "ABX9TyPWyPcQrx9+M6B3b+FjzEPE",
      "include_colab_link": true
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
      "metadata": {
        "id": "view-in-github",
        "colab_type": "text"
      },
      "source": [
        "<a href=\"https://colab.research.google.com/github/Raijeee/journal-Reiji/blob/main/programming_task_1.md\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "47Dj1E4DMcn4",
        "outputId": "f2c47913-858c-4d85-d2ce-2af02089c0e7"
      },
      "source": [
        "#Get user input\n",
        "a=int(input(\"What is your first number? > \"))\n",
        "b=int(input(\"What is your second number? > \"))\n",
        "#See if either both variables are equal to 10 or the sum of both is equal to 10\n",
        "if a==10 or b==10 or a+b==10:\n",
        "#If true print true\n",
        "    print(\"TRUE\")\n",
        "else:\n",
        "#otherwise print false\n",
        "    print(\"FALSE\")"
      ],
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "What is your first number? > 2\n",
            "What is your second number? > 8\n",
            "TRUE\n"
          ]
        }
      ]
    }
  ]
}