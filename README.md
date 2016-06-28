# sshfsmount

sshfsで素早くマウントするためのツール。OSX用

# 準備

[Homebrew Cask](https://caskroom.github.io/) で osxfuseとsshfsを導入

	$ brew tap caskroom/cask
	$ brew cask install osxfuse
	$ brew cask install sshfs
	$ shshfs -V

エラーがでないことを確認する

## インストール

sshfsmountをパスの通った適当なところにコピーして実行権限をつける


# 使う

	$ sshfsmount username@host

