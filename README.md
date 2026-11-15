<div align="center">
  <img src="https://lpluiz.github.io/visada-app/img/visada.png" width="112" alt="VISADA">

  # VISADA

  **Verificação Integrada de Sinal, Alcance, Desdobramento e Antenas**

  Planejamento de enlaces e cobertura de rádio sobre o terreno, de HF a SHF.

  **[Baixar a última versão](../../releases/latest)** · **[Site e demonstrações](https://lpluiz.github.io/visada-app/)**
</div>

---

Este repositório guarda o **programa do VISADA** para baixar, na aba **[Releases](../../releases/latest)**: versões para **Windows** e **Linux**. Não há código-fonte aqui.

## Windows (10 e 11)

1. Baixe o **`visada.exe`**.
2. Dê **dois cliques**. Não há instalador: o programa roda da própria pasta e nada é gravado no sistema (para remover, apague o arquivo).
3. O mapa abre no navegador e aparece um **ícone perto do relógio** (bandeja do sistema). Para fechar, botão direito no ícone.

Se o Windows mostrar **"O Windows protegeu o seu computador"**, clique em **Mais informações** e **Executar assim mesmo** (o programa não tem assinatura digital paga).

## Linux (Debian, Ubuntu, Kali e derivados, 64 bits)

1. Baixe o **`visada.deb`**.
2. Instale com o gerenciador de pacotes:
   ```bash
   sudo apt install ./visada.deb
   ```
   (ou `sudo dpkg -i visada.deb` e, se faltar dependência, `sudo apt -f install`).
3. Abra pelo menu de aplicativos (**VISADA**) ou rode no terminal:
   ```bash
   visada servir
   ```
   O mapa abre no navegador, em `http://localhost:8000`. Para encerrar, feche o terminal ou `Ctrl+C`.
4. Para remover: `sudo apt remove visada`.

## Licença

**Somente uso.** É proibido copiar, distribuir, modificar, descompilar ou usar o programa (ou os seus resultados) para treinar inteligência artificial sem autorização escrita do autor. Texto completo na Release ([LICENCA.txt](../../releases/latest)). Protegido pela Lei 9.609/1998 e pela Lei 9.610/1998.

## Autor

**Luiz Paulo Santos** · [LinkedIn](https://www.linkedin.com/in/lpluiz/)
