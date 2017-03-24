# things-file-upload

## 파일 업로드 컴포넌트.


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

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

## Playing With Your Element

If you wish to work on your element in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polymer-cli

And you can run it via:

    polymer serve

Once running, you can preview your element at
`http://localhost:8080/components/things-alarm/`, where `things-alarm` is the name of the directory containing it.
