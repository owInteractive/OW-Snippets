## GIT

## Corrigi branchs no git
Para voltar para um commit específico, primeiro você deve baixar o plugin [Gitlens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) para o VS Code feito isso instale ele no seu VS Code va até Gitlens no lado direito lá terá uma lista de commits, selecione o commit que você quer voltar e clique com o botão direito será aberto um menu nele você deve clicar em **Reset to Commit** feito isso você deve subir essa alteração para o repositório remoto com o seguinte commando:

```git push --force origin branch```

> Onde branch é a branch que você está atualmente e quer resetar.

Feito isso quem já avançou esse commit e quer voltar ao estado que o repositório remoto está deve utilizar o seguinte commando

```git reset --hard origin/branch```

> Onde branch é a branch que foi corrigida.