微信公众平台 Delphi SDK  

使用方法  
uses  
  WX.App, WX.Common;  
  
var  
  App: IwxApp;  
begin  
&nbsp;&nbsp;App := TwxAppBuilder.New.AppId('编号').Secret('密码').Build;  
&nbsp;&nbsp;App.GetMenuInfo;  
&nbsp;&nbsp;App.GetUserList;  
&nbsp;&nbsp;App.DownloadMedia;   
&nbsp;&nbsp;//...  
&nbsp;&nbsp;// ...  
end;   

引用的其他库  
https://github.com/ahausladen/JsonDataObjects  
https://github.com/danieleteti/delphiredisclient  
  
有疑问联系qq：724464297
