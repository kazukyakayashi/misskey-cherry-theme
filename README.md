# Misskey Cherry theme
Theme for Misskey based on [Cherry colors (KDE Theme)](https://store.kde.org/p/1450880).

## Use

Copy this code on misskey theme editor :

```
{
	id: '0a1757f3-4340-47f1-be7b-f36e5289b727',

	name: 'Cherry',
	author: '@kazukyakayashi@meow.zarchbox.fr',
	desc: 'Theme for Misskey based on Cherry colors (KDE Theme)',

	base: 'dark',

	props: {
		bg: '#1c1c25',
		fg: '#eceff4',
		link: '#ff578b',
		badge: '#7f9bff',
		navBg: '@panel',
		navFg: '@fg',
		panel: '#23232f',
		accent: '#ff578b',
		header: 'rgba(37, 37, 49,0.75)',
		pageBg: '@bg',
		renote: '#64de83',
		divider: 'rgba(32, 32, 32, 0.7)',
		hashtag: '#62c6da',
		mention: '#ff578b',
		navActive: '#ff578b',
		navHoverFg: '#ff578b',
		navIndicator: '@accent',
		driveFolderBg: '@panel',
		fgHighlighted: '@link',
		infoWarnBg: '#ECD379',
		infoWarnFg: '#2e3440',
	},
	author: 'KazukyAkayashi',
}
````

## In Stylus or Misskey CSS editor

```
/* bg for link preview */
.mk-url-preview > a > article {
    background-color: rgba(25, 25, 35, 0.50);
}
```

## Screenshot

![Cherry theme](cherry-misskey-theme-01.png)
