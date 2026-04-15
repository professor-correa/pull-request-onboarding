# Pull Request Onboarding

> Repositório para aprender na prática como contribuir para projetos open source via Pull Request.

---

## O que você vai aprender

Ao concluir esse exercício, você terá feito sua primeira Pull Request em um repositório real — exatamente como funciona no mundo open source.

---

## Lista de presença

Ao seguir o tutorial abaixo, você vai adicionar o seu @ aqui:

@lucascorreaa
@mozzergrozzer
@Felipe
@rafaaagit
@AgblDEV
@Ryan-Silva19
@LucabFusco
@iscaboy 
@thamirisiamdev
@MiriOliveiraFernandes
@yDenBarbosa
@otavio-galdino
@carolinevsant
@Brunobarbosa-Tech
@jaypqueiroz
@GTrajano7
@GoBrazill
@TiagoAntunes-Dev
@cofeezz
@ikaroB-code
@danielfontz
@crizzila
@andreemartinns
@Kaicius
@Vikai23
@Rafa-Dev21

---

## Passo a passo

### 1. Faça o Fork do repositório

Fork é uma cópia do repositório na **sua conta do GitHub**. Você vai trabalhar na sua cópia e depois propor as mudanças para cá.

1. No topo desta página, clique no botão **Fork**
2. Clique em **Create fork**
3. Pronto — agora você tem uma cópia do repositório na sua conta

---

### 2. Clone o seu fork

Clone é baixar o repositório para o seu computador.

Abra o terminal e rode:

```bash
git clone https://github.com/SEU-USUARIO/pull-request-onboarding.git
```

> Substitua `SEU-USUARIO` pelo seu usuário do GitHub

Depois entre na pasta:

```bash
cd pull-request-onboarding
```

---

### 3. Crie uma branch

Branch é uma ramificação do código. Nunca faça alterações direto na branch principal (`develop`).

Crie uma branch com o padrão `docs/added-SEU-USUARIO`:

```bash
git checkout -b docs/added-SEU-USUARIO
```

> Exemplo: se seu usuário é `@joaosilva`, o comando fica:
> `git checkout -b docs/added-joaosilva`

---

### 4. Adicione seu @ na lista de presença

Abra o arquivo `README.md` no seu editor de código e adicione seu usuário do GitHub na **Lista de presença**, seguindo o padrão dos outros:

```
@SEU-USUARIO
```

Salve o arquivo.

---

### 5. Faça o commit e o push

Adicione a alteração ao commit:

```bash
git add README.md
```

Crie o commit com uma mensagem descritiva:

```bash
git commit -m "docs: added @SEU-USUARIO"
```

Envie para o seu fork no GitHub:

```bash
git push origin docs/added-SEU-USUARIO
```

---

### 6. Abra a Pull Request

1. Acesse o seu fork no GitHub (`github.com/SEU-USUARIO/pull-request-onboarding`)
2. Você verá um banner amarelo com o botão **Compare & pull request** — clique nele
3. Verifique que a PR está apontando para o repositório original (`lucascorreaa/pull-request-onboarding`) na branch `develop`
4. Preencha o template da PR:
   - **Turma:** coloque o nome da sua turma
   - **Github Username:** coloque seu `@usuario`
   - **Descrição:** escreva uma frase curta explicando o que você adicionou
   - **Checklist:** marque os itens confirmando que seguiu o padrão
5. Clique em **Create pull request**

---

### 7. Aguarde a revisão

Após abrir a PR, ela será revisada. Você pode receber um dos seguintes retornos:

- **Approved + Merged** — sua contribuição foi aceita! Parabéns, você fez sua primeira PR open source
- **Changes requested** — há algo para ajustar. Leia o comentário, faça a correção no mesmo branch e faça um novo push — a PR atualiza automaticamente

---

## Duvidas frequentes

**Esqueci de criar a branch e fiz as alterações na `develop`, e agora?**
Crie a branch agora com `git checkout -b docs/added-SEU-USUARIO` — suas alterações não commitadas vão junto.

**Meu fork está desatualizado em relação ao repositório original, e agora?**
No GitHub, na página do seu fork, clique em **Sync fork** > **Update branch**.

**Posso editar diretamente pelo GitHub sem clonar?**
Sim! No arquivo `README.md`, clique no ícone de lápis (Edit), faça a alteração, e na hora de salvar o GitHub vai criar a branch automaticamente para você.

---

## Estrutura do repositório

```
pull-request-onboarding/
├── .github/
│   └── PULL_REQUEST_TEMPLATE.md   # Template que aparece ao abrir uma PR
└── README.md                      # Este arquivo
```
