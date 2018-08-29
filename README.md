# webkit-sassui-ios-modal
> Webkit sass for ios basic modal

## usage:
+ https://afeiship.github.io/webkit-sassui-ios-modal/

## resources:
+ https://github.com/afeiship/generator-webkit-sassui

## become alert/confirm:
```scss
  &[data-type=alert]{
    >.ft{
      button{
        width:100%;
      }
    }
  }

  &[data-type=confirm]{
    >.ft{
      display: flex;
      button{
        flex:1;
        & + button{
          border-left: 0.55px solid #dbdbdf;
        }
      }
    }
  }
```