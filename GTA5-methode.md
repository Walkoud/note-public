
## Tuto : Optimisation Cayo (YimMenu + No Save)

### 1. Prérequis et Téléchargements
*   **YimMenuV2 (DLL) :** [Release Nightly](https://github.com/YimMenu/YimMenuV2/releases/tag/nightly)
*   **Xenos Injector :** [Version 2.3.2](https://github.com/DarthTon/Xenos/releases/tag/2.3.2)
*   **AutoHotkey :** [Installateur AHK](https://www.autohotkey.com/download/ahk-install.exe)
*   **Script NoSave :** [V1.2_nosave.ahk](https://drive.google.com/file/d/1sTtpYJEHCBQioJw1SVnVMEi4MBY1HlDM/view)

---

### 2. Désactiver BattlEye (Pour l'injection)
**Avant de lancer le jeu :**
*   **Rockstar Launcher :** Paramètres > GTA V > **Décoche** la case BattlEye.
*   **Steam :** Clic droit sur le jeu > Propriétés > Options de lancement > Ajoute `-nobattleye`.
*   **Vérification :** Lance le jeu. Arrivé au menu, ouvre le gestionnaire des tâches pour vérifier qu'aucun processus BattlEye ne tourne.

---

### 3. Injection et Setup du Heist
1.  **Injecter :** Ouvre **Xenos**, sélectionne le processus `GTA5.exe` (Enhanced) et ajoute `YimMenuV2.dll`. Clique sur **Inject**.
2.  **Validation :** Appuie sur **OK** sur le popup qui s'affiche en jeu.
3.  **Mode Histoire :** Va d'abord en mode histoire, puis appuie sur **Insert**.
4.  **Session :** `Session` -> `Invite only` -> `Join`.
5.  **Setup :** Une fois dedans, `Insert` -> `Recovery menu` -> `Heist setup`. Choisis l'arme **"Saboteur"** puis appuie sur **Setup**.
6.  **Refresh :** `Session` -> `Invite only` -> `Join` pour rafraîchir. Va vérifier dans ton Kosatka si c'est ok.
7.  **Reset :** Ferme le jeu. **Remets BattlEye** (recoche dans Rockstar et supprime l'option dans Steam).

---

### 4. Procédure No-Save (Cayo à l'infini)
**Attention : Ton PARE-FEU doit être ACTIF.**

1.  **Lancement :** Lance le jeu normalement (avec BattlEye) et va dans ton Kosatka.
2.  **Script :** Lance le fichier `V1.2_nosave.ahk`.
    *   `CTRL + F9` : Activer le No Save.
    *   `CTRL + F12` : Désactiver le No Save.
3.  **Test de sécurité (Obligatoire) :** Avant de lancer le braquage, fais `CTRL + F9` puis fais `ALT + F4`.
    *   Si ça affiche un message d'**erreur de sauvegarde**, c'est bon.
    *   Si ça ne dit rien ou que ça veut fermer direct, c'est pas bon, ne lance rien.
4.  **Le Braquage :** Lance ton Cayo et fais-le jusqu'au bout.
5.  **La Fin :** Une fois le braquage fini, quand tu es devant la maison d'El Rubio, **va en mode histoire**.
6.  **Synchronisation :**
    *   Une fois que tu es en mode histoire, fais `CTRL + F12`.
    *   Retourne maintenant en mode en ligne.
7.  **Sauvegarde finale :** Tu as ton argent. Fais `ALT + F4` maintenant pour sauvegarder. Si tu vois "Sauvegarde réussie", c'est parfait : tu as le cash et ton Cayo est toujours prêt au Kosatka.
