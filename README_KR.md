# things-file-upload

## 이는 파일을 업로드하는 컴포넌트이다.


Example:

```html
     <things-file-upload target="upload" nodrop method="POST" timeout="300000" >
     </things-file-upload>
```
i18n:
```js
Default:
      {
      dropFiles: {
          one: Things.DataGlobal.t('text.drop_file_here'),
          many: Things.DataGlobal.t('text.drop_files_here')
      },
      addFiles: {
          one: Things.DataGlobal.t('text.select_file'),
          many: Things.DataGlobal.t('text.add_files')
      },
      cancel: Things.DataGlobal.t('text.cancel'),
      cancelAll: Things.DataGlobal.t('text.cancel_all'),
      error: {
          tooManyFiles: Things.DataGlobal.t('text.too_many_files'),
          fileIsTooBig: Things.DataGlobal.t('text.file_is_too_big'),
          incorrectFileType: Things.DataGlobal.t('text.incorrect_file_type')
      },
      uploading: {
          status: {
              connecting: Things.DataGlobal.t('text.connecting'),
              stalled: Things.DataGlobal.t('text.stalled'),
              processing: Things.DataGlobal.t('text.processing_file')
          },
          remainingTime: {
              prefix: Things.DataGlobal.t('text.remaining_time'),
              unknown: Things.DataGlobal.t('text.unknown_remaining_time')
          },
          error: {
              serverUnavailable: Things.DataGlobal.t('text.server_unavailable'),
              unexpectedServerError: Things.DataGlobal.t('text.unexpected_server_error'),
              forbidden: Things.DataGlobal.t('text.forbidden')
          }
      },
      units: {
          size: ['B', 'kB', 'MB', 'GB', 'TB', 'PB', 'EB', 'ZB', 'YB']
      }
  }

```
Example:


*****
</br></br>

```html
     <things-file-upload target="upload" i18n="{{i18n}}" method="POST" timeout="300000" >
     </things-file-upload>
     <things-file-upload target="upload" nodrop method="POST" timeout="300000" >
     </things-file-upload>
```

## Dependencies

element의 종속성은 [Bower](http://bower.io/)를 통해 관리되며, 아래의 방법을 통해 설치할 수 있다.

    npm install -g bower

다음, element의 종속성을 다운로드한다.

    bower install

## Playing With Your Element

element를 독립적으로 처리하려면 [Polyserve](https://github.com/PolymerLabs/polyserve)를 사용하여 element의 bower 의존성을 유지하도록 하며, 이는 아래의 방법을 통해 설치할 수 있다.

    npm install -g polymer-cli

그리고, 아래의 방법을 통해 실행할 수 있다.

    polymer serve

element를 실행한 경우, `things-alarm`이 디렉토리 이름으로 포함되어 있는 `http://localhost:8080/components/things-alarm/`을 통해 이를 미리 확인할 수 있다. 
