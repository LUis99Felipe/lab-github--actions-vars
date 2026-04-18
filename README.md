RESPOSTAS:

Por que a Secret aparece no log como ** e a variável aparece
normalmente?
R: Porque a váriavel é do tipo secrect, como uma senha armazenada em um banco de dados com criptografia

O Job deploy_app consegue ler a variável BUILD_VERSION criada no Job
build_app? Por quê?
R:Não, porque a váriavel BUILD_VERSION é do tipo local. A váriavel é acessada no próprio Git Hub na parte de "Vars and Secrets"
