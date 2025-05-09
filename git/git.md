* Windows: just download exe and run
* Fedora:
    - `sudo dnf install git -y`

* Git Credential Manager(Windows don't need)
    - `sudo dnf install pass -y`

    - ```
        curl -L https://aka.ms/gcm/linux-install-source.sh | sh
        git-credential-manager configure 
        gpg --gen-key
        pass init <gpg_uuid>
        git config --global credential.credentialStore gpg
        ```
`git config --global user.name "Your Name"`

`git config --global user.email "email"`
