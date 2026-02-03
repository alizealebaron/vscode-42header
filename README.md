<p align="center">
  <img src="https://raw.githubusercontent.com/kube/vscode-42header/master/42.png" width="120"/>
</p>
<h3 align="center">
  <em>Un header parfait comprend à minima un canard</em>
</h3>

---

## ⚠️ Avant propos

> **Ce projet n'a pas été crée par moi**
>
> Cette extension est un **double** de l'original [vscode-42header by kube](https://githubcom/kube/vscode-42header).
>

## 🦆 42header

```bash
******************************************************************************
*       _  _     ____                    ,~~.                                *
*      | || |   |___ \              ,   (  ^ )>                              *
*      | || |_    __) |             )\~~'   (       _      _      _          *
*      |__   _|  / __/             (  .__)   )    >(.)__ <(^)__ =(o)__       *
*         |_|   |_____| .fr         \_.____,*      (___/  (___/  (___/       *
*                                                                            *
******************************************************************************
* @name   : vs-code_duck-header                                              *
* @author : alebaron                                                         *
*                                                                            *
* @creation : 2013/11/18 13:37:42 by kube                                    *
* @update   : 2026/02/03 14:33:42 by alebaron                                *
******************************************************************************
```

## 💻 Usage

### Insertion du header
 - **macOS** : <kbd>⌘</kbd> + <kbd>⌥</kbd> + <kbd>H</kbd>
 - **Linux** / **Windows** : <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>H</kbd>.

Ce header ce met automatiquement à jour à chaque sauvegarde.

## 📜 Configuration

Les valeurs par défaut pour **username** et **email** sont importées depuis les variables d’environnement.

Pour remplacer ces valeurs, spécifiez ces propriétés dans les *paramètres utilisateur*.

```ts
{
  "42header.username": string,
  "42header.email": string
}
```
