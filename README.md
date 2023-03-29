<div align=center>
	<img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=200&section=header&text=Object%20Thumbnail%20Maker&fontSize=50" />
</div>
<br>
<br>

![image](https://user-images.githubusercontent.com/11285283/228478547-8d6f340a-6eb8-4863-940d-8163df40ede6.png)

<br>
<br>
<br>
3Dオブジェクトのサムネイルを設定し、Pngファイルとして、保存できるユーティリティです。<br>
これを利用して、アイテムのアイコンを素早く製作するなど、様々な方法で使用できます。
<br>
<br>

[設定 : CaptureManager]
| 変数名          |タイプ|        　　 説明                  |
|----------------|------|-----------------------------------|
| PrefixString   | 共通 | 保存されるPngファイルの名前接頭辞  |
|   BgColors     | 共通 | 保存されるPngファイルの背景色      |
|  CaptureSize   | 共通 | 保存されるPngファイルのサイズ      |
| RenderTexture  | 共通 | 保存時に使用されるRender Texture   |
|   ObjectName   | 單數 | 保存時にPngファイルの名前          |
| CaptureObjects | 複数 | 一括保存するオブジェクト配列       |

<br>
<br>
・Bg Colors、Capture Sizeの追加の場合、スクリプトを修正して追加する必要があります。
<br>
<br>
[オブジェクトの回転及びサイズ変更方法]<br>
実行中、キャプチャ領域で、クリックした後、ドラッグを利用して回転し<br>
マウスホイールボタンを利用して、拡大や縮小することができます。<br>
これは、單數のキャプチャである場合にのみ、使用できます。<br>
<br>
<br>
[單數のオブジェクトキャプチャ]<br>
1 つのオブジェクトをキャプチャする場合、Obj_Rootの下にキャプチャするオブジェクトを配置し、ポジションを0に初期化します。<br>
その後、CaptureManagerで設定が終わったら、シーンを実行し、オブジェクトの回転及びサイズを修正した後、<br>
Captureボタンをクリックして、キャプチャすることができます。<br>
<br>
<br>
[複数のオブジェクトキャプチャ]<br>
複数のオブジェクトをキャプチャする場合、Obj_Rootの以下のオブジェクトをすべて削除した後、CaptureManagerで設定が終了したら<br>
シーンを実行し、All Capture ボタンをクリックして、登録されたオブジェクトを一括キャプチャすることができます。<br>
この場合、オブジェクトの回転および拡大縮小に関しては、CamerasのCapture_Cameraのポジションを利用して設定する必要があります。<br>

<br>
<br> ========================================================================= <br>
<br>

3D오브젝트의 썸네일을 설정하고 Png 파일로 저장할 수 있는 유틸리티입니다.<br>
이를 이용하여 아이템의 아이콘을 빠르게 제작하는 등의 여러 가지 방법으로 사용할 수 있습니다.
<br>
<br>

[설정 : CaptureManager]
| 변수명          | 타입 |         설명                  |
|----------------|------|-------------------------------|
| PrefixString   | 공통 | 저장될 Png파일의 이름 접두사   |
|   BgColors     | 공통 | 저장될 Png파일의 배경 색상     |
|  CaptureSize   | 공통 | 저장될 Png파일의 크기          |
| RenderTexture  | 공통 | 저장 시 사용될 RenderTexture   |
|   ObjectName   | 단수 | 저장 시 Png파일의 이름         |
| CaptureObjects | 복수 | 일괄 저장할 오브젝트 배열      |

<br>
<br>
・BgColors, CaptureSize 추가의 경우 스크립트를 수정하여 추가해야 합니다.
<br>
<br>
[오브젝트의 회전 및 크기 변경 방법]<br>
실행 중 캡처 영역에서 클릭 후 드래그를 이용하여 회전하고<br>
마우스 휠 버튼을 이용하여 확대 및 축소를 할 수 있습니다.<br>
이는 단수의 캡처일 경우에만 사용할 수 있습니다.<br>
<br>
<br>
[단수의 오브젝트 캡처]<br>
하나의 오브젝트를 캡처할 경우 Obj_Root의 아래 캡처할 오브젝트를 배치하고 포지션을 0으로 초기화합니다.<br>
이후 CaptureManager에서 설정이 끝나면 씬을 실행하고 오브젝트 회전 및 크기를 수정 후 Capture 버튼을 클릭하여 캡처할 수 있습니다.
<br>
<br>
[복수의 오브젝트 캡처]<br>
복수의 오브젝트를 캡처할 경우 Obj_Root의 아래 오브젝트를 모두 삭제 후 CaptureManager에서 설정이 끝나면<br>
씬을 실행하고 All Capture 버튼을 클릭하여 등록된 오브젝트를 일괄 캡처할 수 있습니다.<br>
이 경우 오브젝트의 회전 및 확대 축소에 관해서는 Cameras의 Capture_Camera의 포지션을 이용해서 설정해야 합니다.<br>

