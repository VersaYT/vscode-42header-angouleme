<img
  src="https://raw.githubusercontent.com/kube/vscode-42header/master/42.png"
  width=128>

# 42 Header for VSCode

This extension provides the 42 header integration in VS Code.

This is a patched version for the 42angouleme email address.

```bash
# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    vscode-42header                                    :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: kube <yourid..@student.42angouleme.fr>     +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2013/11/18 13:37:42 by kube              #+#    #+#              #
#    Updated: 2026/10/27 20:43:04 by VersaYT          ###   ########.fr        #
#                                                                              #
# **************************************************************************** #
```

## Install

Launch Quick Open with <kbd>⌘</kbd>+<kbd>P</kbd> and enter
```
ext install 42header
```

## Usage

### Insert a header
 - **macOS** : <kbd>⌘</kbd> + <kbd>⌥</kbd> + <kbd>H</kbd>
 - **Linux** / **Windows** : <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>H</kbd>.

Header is automatically updated on save.


## Configuration

Default values for **username** and **email** are imported from environment variables.

To override these values, specify these properties in *User Settings* :

```ts
{
  "42header.username": string,
  "42header.email": string
}
```


## Issues

In case of a bug, or missing feature, please create a [Github Pull Request](https://github.com/kube/vscode-42header/pulls).

## License

MIT
