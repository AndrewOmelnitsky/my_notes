- tegs: #JS #Electron
-
- `api base url = /api/vN/` - url по которому будет доступен api
  `api port = 3000` - порт по которому будет доступен api
## Базовые URLs
-----
- ## Модель данных о текушей песни
  НУжно будет возвращять дать возможность получать все поя по api
  ```js
  const songInfo = {
  	title: "",
  	artist: "",
  	views: 0,
  	uploadDate: "",
  	imageSrc: "",
  	image: null,
  	isPaused: undefined,
  	songDuration: 0,
  	elapsedSeconds: 0,
  	url: "",
  	album: undefined,
  	videoId: "",
  	playlistId: "",
  };
  ```