git config --show-origin credential.helper
위치 확인

[credential]
        helper = osxkeychain


설정 확인
git config --local credential.helper
git config --global credential.helper
git config --system credential.helper


unset 하는법
git config --system --unset credential.helper




 /usr/local/etc  git config --show-origin credential.helper     ✔  16:59:52
file:/Applications/Xcode.app/Contents/Developer/usr/share/git-core/gitconfig	osxkeychain