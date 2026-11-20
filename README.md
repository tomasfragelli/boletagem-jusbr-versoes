# Boletagem — versões para instalar

Este repositório guarda só os instaladores do Boletagem e o arquivo que informa a versão mais nova
(`atualizacao.json`). O repositório de desenvolvimento é privado.

## Como instalar

1. Baixe `Boletagem-Setup-<versão>.exe` da versão mais recente, na aba **Releases**.
2. Execute o arquivo. A instalação é por usuário e não precisa de administrador.
3. É preciso ter o Google Chrome instalado. O instalador não o traz.
4. O Windows pode mostrar "Windows protegeu seu computador", porque o instalador não tem assinatura digital.
   Clique em **Mais informações** e depois em **Executar assim mesmo**.

## Como as atualizações funcionam

Ao abrir, o programa confere o `atualizacao.json` deste repositório. Se houver uma versão nova, ele mostra um
aviso. Só com a confirmação da pessoa o programa baixa o instalador, confere o SHA-256 e instala. O banco, a
planilha, as configurações e os relatórios não são tocados.

## Licença

Copyright (C) 2026 Tomás Fragelli

O Boletagem é software livre, distribuído sob a GNU General Public License versão 3 ou, a seu critério,
qualquer versão posterior (GPL-3.0-or-later), SEM NENHUMA GARANTIA. Texto da licença:
<https://www.gnu.org/licenses/gpl-3.0.html>.

O instalador contém o código-fonte do programa em texto legível (pasta `app\boletagem` dentro da
instalação). Na pasta `app` ficam também `LICENSE.txt` e `THIRD_PARTY_NOTICES.txt` (licenças dos componentes de
terceiros).

## Para quem mantém

Cada versão é uma Release com dois arquivos: o `.exe` e o `atualizacao.json`.

**Não renomeie, não apague e não torne privado este repositório.** A URL dele fica gravada em todos os
instaladores já distribuídos; se ela deixar de funcionar, essas instalações não recebem mais atualizações.
