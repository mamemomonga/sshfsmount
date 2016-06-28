# sshfsmount

OSXで簡単にsshfsでマウントするスクリプト

# 準備

[Homebrew Cask](https://caskroom.github.io/) で osxfuseとsshfsを導入

	brew tap caskroom/cask
	brew cask install osxfuse
	brew cask install sshfs

	sshfs -V

エラーがでないことを確認する

## インストール

sshfsmountをパスの通った適当なところにコピーして実行権限をつける


# 使う

	sshfsmount username@host

