# kubectl-aliases

>Here's to the lazy one's.
>The troublesome people.
>The productive people.
>The ones who see things completely but are unwilling to write down everything.
>
>They're not fond of writing big CLI commands.
>And they have no respect for the huge descriptive CLI flags.
>
>You can  glorify their short productive tips, criticise their aliases for absurdity.
>About the only you can't do is to ignore their tips.
>
>Because they change the commands you type everyday.
>
>They push the lazy human race forward.
>
>While some may see them as the lazy ones,
>we see a intellect unfond of writing long CLI commands everyday.
>
>Because the people who are lazy enough to think
>they can write aliases, are the ones who do.

## Description:

1. This repository contains some aliases I use everyday for interacting with Kubernetes. More aliases will be added as time permits.
2. The pattern for aliases is quite visible.
   ```
   k - kubectl
   get/del/edit/exp - get/delete/edit/expose
   svc/dep/pvc - service/deployment/pvc
   ```
3. Exception: `kedit` since it is convenient to write a single function for svc,dep,etc. 

## Prerequisities:
1. Being lazy

## How to use:
1. Check `aliases` file in the repository containing the kubectl aliases.
2. Copy everything (if you're lazy) and add them into `~/.bashrc` or `~/.zshrc`.
3. Run `source ~/.bashrc` or `source ~/.zshrc`

## Contributing:
Contributions are welcome as long as they're pushing the lazy human race forward.

**P.S.** That doesn't mean PR descriptions should be short. Commits should be `signed` and having appropriate descriptions

