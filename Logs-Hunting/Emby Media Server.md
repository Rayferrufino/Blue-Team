# Normal media server logs (https://emby.media); including auth logs w/ valid user:pass

```bash
2019-08-25 17:41:39.587 Info HttpServer: HTTP GET http://localhost:8096/emby/System/ActivityLog/Entries?startIndex=0&limit=7&minDate=2019-08-24T21%3A41%3A39.571Z&hasUserId=true. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 17:41:39.592 Info HttpServer: HTTP Response 200 to ::1. Time: 5ms. http://localhost:8096/emby/System/ActivityLog/Entries?startIndex=0&limit=7&minDate=2019-08-24T21%3A41%3A39.571Z&hasUserId=true
2019-08-25 17:41:39.598 Info HttpServer: WS http://192.168.56.101:8096/embywebsocket?api_key=1bc5b41dc86648ae960fb309fd16850e&deviceId=TW96aWxsYS81LjAgKFgxMTsgTGludXggeDg2XzY0OyBydjo2MC4wKSBHZWNrby8yMDEwMDEwMSBGaXJlZm94LzYwLjB8MTU2Njc2OTI3OTQ5OA11. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 17:41:39.617 Info HttpServer: HTTP GET http://localhost:8096/emby/System/ActivityLog/Entries?startIndex=0&limit=7&minDate=2019-08-24T21%3A41%3A39.616Z&hasUserId=true. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 17:41:39.619 Info HttpServer: HTTP Response 200 to ::1. Time: 3ms. http://localhost:8096/emby/System/ActivityLog/Entries?startIndex=0&limit=7&minDate=2019-08-24T21%3A41%3A39.616Z&hasUserId=true
2019-08-25 17:41:39.623 Info HttpServer: HTTP GET http://localhost:8096/emby/System/ActivityLog/Entries?startIndex=0&limit=4&minDate=2019-08-18T21%3A41%3A39.619Z&hasUserId=false. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 17:41:39.628 Info HttpServer: HTTP Response 200 to ::1. Time: 5ms. http://localhost:8096/emby/System/ActivityLog/Entries?startIndex=0&limit=4&minDate=2019-08-18T21%3A41%3A39.619Z&hasUserId=false
2019-08-25 17:41:39.628 Info HttpServer: HTTP GET http://localhost:8096/emby/System/ActivityLog/Entries?startIndex=0&limit=4&minDate=2019-08-18T21%3A41%3A39.623Z&hasUserId=false. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 17:41:39.633 Info HttpServer: HTTP Response 200 to ::1. Time: 5ms. http://localhost:8096/emby/System/ActivityLog/Entries?startIndex=0&limit=4&minDate=2019-08-18T21%3A41%3A39.623Z&hasUserId=false
2019-08-25 17:41:39.633 Info HttpServer: HTTP GET http://localhost:8096/emby/System/ActivityLog/Entries?startIndex=0&limit=7&minDate=2019-08-24T21%3A41%3A39.628Z&hasUserId=true. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 17:41:39.636 Info HttpServer: HTTP Response 200 to ::1. Time: 3ms. http://localhost:8096/emby/System/ActivityLog/Entries?startIndex=0&limit=7&minDate=2019-08-24T21%3A41%3A39.628Z&hasUserId=true
2019-08-25 17:41:39.636 Info HttpServer: HTTP GET http://localhost:8096/emby/System/ActivityLog/Entries?startIndex=0&limit=4&minDate=2019-08-18T21%3A41%3A39.632Z&hasUserId=false. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 17:41:39.639 Info HttpServer: HTTP Response 200 to ::1. Time: 3ms. http://localhost:8096/emby/System/ActivityLog/Entries?startIndex=0&limit=4&minDate=2019-08-18T21%3A41%3A39.632Z&hasUserId=false
2019-08-25 17:41:39.639 Info HttpServer: HTTP GET http://localhost:8096/emby/System/ActivityLog/Entries?startIndex=0&limit=7&minDate=2019-08-24T21%3A41%3A39.621Z&hasUserId=true. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 17:41:39.652 Info HttpServer: HTTP Response 200 to ::1. Time: 12ms. http://localhost:8096/emby/System/ActivityLog/Entries?startIndex=0&limit=7&minDate=2019-08-24T21%3A41%3A39.621Z&hasUserId=true
2019-08-25 17:41:39.652 Info HttpServer: HTTP GET http://192.168.56.101:8096/emby/DisplayPreferences/usersettings?userId=63999abed9ce407582d00622b8f17cf4&client=emby. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 17:41:39.655 Info HttpServer: HTTP Response 200 to 192.168.56.102. Time: 3ms. http://192.168.56.101:8096/emby/DisplayPreferences/usersettings?userId=63999abed9ce407582d00622b8f17cf4&client=emby
2019-08-25 17:41:39.789 Info HttpServer: HTTP POST http://192.168.56.101:8096/emby/Sessions/Capabilities/Full. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 17:41:39.797 Info HttpServer: HTTP Response 204 to 192.168.56.102. Time: 8ms. http://192.168.56.101:8096/emby/Sessions/Capabilities/Full
2019-08-25 17:41:39.896 Info HttpServer: HTTP GET http://192.168.56.101:8096/emby/ScheduledTasks. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 17:41:39.898 Info HttpServer: HTTP Response 200 to 192.168.56.102. Time: 2ms. http://192.168.56.101:8096/emby/ScheduledTasks
2019-08-25 17:41:39.898 Info HttpServer: HTTP GET http://192.168.56.101:8096/emby/System/Info. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 17:41:39.899 Info HttpServer: HTTP Response 200 to 192.168.56.102. Time: 1ms. http://192.168.56.101:8096/emby/System/Info
2019-08-25 17:41:39.899 Info HttpServer: HTTP GET http://192.168.56.101:8096/emby/News/Product?StartIndex=0&Limit=4. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 17:41:39.903 Info HttpServer: HTTP Response 200 to 192.168.56.102. Time: 4ms. http://192.168.56.101:8096/emby/News/Product?StartIndex=0&Limit=4
2019-08-25 17:41:39.903 Info HttpServer: HTTP GET http://192.168.56.101:8096/emby/System/ActivityLog/Entries?startIndex=0&limit=7&minDate=2019-08-24T21%3A41%3A41.041Z&hasUserId=true. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 17:41:39.904 Info HttpServer: HTTP Response 200 to 192.168.56.102. Time: 1ms. http://192.168.56.101:8096/emby/System/ActivityLog/Entries?startIndex=0&limit=7&minDate=2019-08-24T21%3A41%3A41.041Z&hasUserId=true
2019-08-25 17:41:39.904 Info HttpServer: HTTP GET http://192.168.56.101:8096/emby/Sessions?ActiveWithinSeconds=900. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 17:41:39.906 Info HttpServer: HTTP Response 200 to 192.168.56.102. Time: 1ms. http://192.168.56.101:8096/emby/Sessions?ActiveWithinSeconds=900
2019-08-25 17:41:39.912 Info HttpServer: HTTP GET http://192.168.56.101:8096/emby/System/ActivityLog/Entries?startIndex=0&limit=4&minDate=2019-08-18T21%3A41%3A41.042Z&hasUserId=false. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 17:41:39.914 Info HttpServer: HTTP Response 200 to 192.168.56.102. Time: 1ms. http://192.168.56.101:8096/emby/System/ActivityLog/Entries?startIndex=0&limit=4&minDate=2019-08-18T21%3A41%3A41.042Z&hasUserId=false
2019-08-25 17:41:39.914 Info HttpServer: HTTP GET http://192.168.56.101:8096/emby/LiveTv/Recordings?UserId=63999abed9ce407582d00622b8f17cf4&IsInProgress=true&Fields=CanDelete%2CPrimaryImageAspectRatio&EnableTotalRecordCount=false&EnableImageTypes=Primary%2CThumb%2CBackdrop. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 17:41:39.915 Info HttpServer: HTTP Response 200 to 192.168.56.102. Time: 1ms. http://192.168.56.101:8096/emby/LiveTv/Recordings?UserId=63999abed9ce407582d00622b8f17cf4&IsInProgress=true&Fields=CanDelete%2CPrimaryImageAspectRatio&EnableTotalRecordCount=false&EnableImageTypes=Primary%2CThumb%2CBackdrop
2019-08-25 17:41:39.915 Info HttpServer: HTTP GET http://192.168.56.101:8096/emby/web/configurationpages?pageType=PluginConfiguration&EnableInMainMenu=true. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 17:41:39.916 Info HttpServer: HTTP Response 200 to 192.168.56.102. Time: 1ms. http://192.168.56.101:8096/emby/web/configurationpages?pageType=PluginConfiguration&EnableInMainMenu=true
2019-08-25 17:41:39.970 Info HttpServer: HTTP GET http://192.168.56.101:8096/web/bower_components/emby-webcomponents/themes/light/theme.json?v=4.2.1.0&r=0. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 17:41:39.970 Info HttpServer: HTTP Response 200 to 192.168.56.102. Time: 1ms. http://192.168.56.101:8096/web/bower_components/emby-webcomponents/themes/light/theme.json?v=4.2.1.0&r=0
2019-08-25 17:41:39.988 Info HttpServer: HTTP GET http://192.168.56.101:8096/web/bower_components/emby-webcomponents/themes/logodark.png. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 17:41:39.989 Info HttpServer: HTTP Response 200 to 192.168.56.102. Time: 1ms. http://192.168.56.101:8096/web/bower_components/emby-webcomponents/themes/logodark.png
```
# Emby media server logging bruteforce attack with 1/7 successful login attempts
```bash
2019-08-25 18:55:02.631 Info HttpServer: HTTP POST http://192.168.56.101:8096/emby/Users/authenticatebyname. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 18:55:02.632 Error UserManager: Error authenticating with provider Default
    *** Error Report ***
    Version: 4.2.1.0
    Command line: /opt/emby-server/system/EmbyServer.dll -programdata /var/lib/emby -ffdetect /opt/emby-server/bin/ffdetect -ffmpeg /opt/emby-server/bin/ffmpeg -ffprobe /opt/emby-server/bin/ffprobe -restartexitcode 3 -updatepackage emby-server-deb_{version}_amd64.deb
    Operating system: Unix 4.19.0.5
    64-Bit OS: True
    64-Bit Process: True
    User Interactive: True
    Runtime: file:///opt/emby-server/system/System.Private.CoreLib.dll
    Processor count: 1
    Program data path: /var/lib/emby
    Application directory: /opt/emby-server/system
    System.Exception: System.Exception: Invalid username or password
       at Emby.Server.Implementations.Library.DefaultAuthenticationProvider.Authenticate(String username, String password, User resolvedUser)
       at Emby.Server.Implementations.Library.UserManager.AuthenticateWithProvider(IAuthenticationProvider provider, String username, String password, User resolvedUser, CancellationToken cancellationToken)
    Source: Emby.Server.Implementations
    TargetSite: System.Threading.Tasks.Task`1[MediaBrowser.Controller.Authentication.ProviderAuthenticationResult] Authenticate(System.String, System.String, MediaBrowser.Controller.Entities.User)

2019-08-25 18:55:02.632 Info HttpClient: POST https://connect.emby.media/service/user/authenticate
2019-08-25 18:55:02.793 Info UserManager: Authentication request for emby has been denied.
2019-08-25 18:55:02.793 Warn HttpServer: AUTH-ERROR: 192.168.56.102 - Invalid user or password entered.
2019-08-25 18:55:02.793 Error HttpServer: Invalid user or password entered.
2019-08-25 18:55:02.794 Info HttpServer: HTTP Response 401 to 192.168.56.102. Time: 162ms. http://192.168.56.101:8096/emby/Users/authenticatebyname
2019-08-25 18:55:02.927 Info HttpServer: HTTP POST http://192.168.56.101:8096/emby/Users/authenticatebyname. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 18:55:02.928 Error UserManager: Error authenticating with provider Default
    *** Error Report ***
    Version: 4.2.1.0
    Command line: /opt/emby-server/system/EmbyServer.dll -programdata /var/lib/emby -ffdetect /opt/emby-server/bin/ffdetect -ffmpeg /opt/emby-server/bin/ffmpeg -ffprobe /opt/emby-server/bin/ffprobe -restartexitcode 3 -updatepackage emby-server-deb_{version}_amd64.deb
    Operating system: Unix 4.19.0.5
    64-Bit OS: True
    64-Bit Process: True
    User Interactive: True
    Runtime: file:///opt/emby-server/system/System.Private.CoreLib.dll
    Processor count: 1
    Program data path: /var/lib/emby
    Application directory: /opt/emby-server/system
    System.Exception: System.Exception: Invalid username or password
       at Emby.Server.Implementations.Library.DefaultAuthenticationProvider.Authenticate(String username, String password, User resolvedUser)
       at Emby.Server.Implementations.Library.UserManager.AuthenticateWithProvider(IAuthenticationProvider provider, String username, String password, User resolvedUser, CancellationToken cancellationToken)
    Source: Emby.Server.Implementations
    TargetSite: System.Threading.Tasks.Task`1[MediaBrowser.Controller.Authentication.ProviderAuthenticationResult] Authenticate(System.String, System.String, MediaBrowser.Controller.Entities.User)

2019-08-25 18:55:02.928 Info HttpClient: POST https://connect.emby.media/service/user/authenticate
2019-08-25 18:55:02.966 Info UserManager: Authentication request for emby has been denied.
2019-08-25 18:55:02.967 Warn HttpServer: AUTH-ERROR: 192.168.56.102 - Invalid user or password entered.
2019-08-25 18:55:02.967 Error HttpServer: Invalid user or password entered.
2019-08-25 18:55:02.967 Info HttpServer: HTTP Response 401 to 192.168.56.102. Time: 41ms. http://192.168.56.101:8096/emby/Users/authenticatebyname
2019-08-25 18:55:03.149 Info HttpServer: HTTP POST http://192.168.56.101:8096/emby/Users/authenticatebyname. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 18:55:03.152 Error UserManager: Error authenticating with provider Default
    *** Error Report ***
    Version: 4.2.1.0
    Command line: /opt/emby-server/system/EmbyServer.dll -programdata /var/lib/emby -ffdetect /opt/emby-server/bin/ffdetect -ffmpeg /opt/emby-server/bin/ffmpeg -ffprobe /opt/emby-server/bin/ffprobe -restartexitcode 3 -updatepackage emby-server-deb_{version}_amd64.deb
    Operating system: Unix 4.19.0.5
    64-Bit OS: True
    64-Bit Process: True
    User Interactive: True
    Runtime: file:///opt/emby-server/system/System.Private.CoreLib.dll
    Processor count: 1
    Program data path: /var/lib/emby
    Application directory: /opt/emby-server/system
    System.Exception: System.Exception: Invalid username or password
       at Emby.Server.Implementations.Library.DefaultAuthenticationProvider.Authenticate(String username, String password, User resolvedUser)
       at Emby.Server.Implementations.Library.UserManager.AuthenticateWithProvider(IAuthenticationProvider provider, String username, String password, User resolvedUser, CancellationToken cancellationToken)
    Source: Emby.Server.Implementations
    TargetSite: System.Threading.Tasks.Task`1[MediaBrowser.Controller.Authentication.ProviderAuthenticationResult] Authenticate(System.String, System.String, MediaBrowser.Controller.Entities.User)

2019-08-25 18:55:03.152 Info HttpClient: POST https://connect.emby.media/service/user/authenticate
2019-08-25 18:55:03.196 Info UserManager: Authentication request for emby has been denied.
2019-08-25 18:55:03.197 Warn HttpServer: AUTH-ERROR: 192.168.56.102 - Invalid user or password entered.
2019-08-25 18:55:03.197 Error HttpServer: Invalid user or password entered.
2019-08-25 18:55:03.197 Info HttpServer: HTTP Response 401 to 192.168.56.102. Time: 48ms. http://192.168.56.101:8096/emby/Users/authenticatebyname
2019-08-25 18:55:03.465 Info HttpServer: HTTP POST http://192.168.56.101:8096/emby/Users/authenticatebyname. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 18:55:03.469 Error UserManager: Error authenticating with provider Default
    *** Error Report ***
    Version: 4.2.1.0
    Command line: /opt/emby-server/system/EmbyServer.dll -programdata /var/lib/emby -ffdetect /opt/emby-server/bin/ffdetect -ffmpeg /opt/emby-server/bin/ffmpeg -ffprobe /opt/emby-server/bin/ffprobe -restartexitcode 3 -updatepackage emby-server-deb_{version}_amd64.deb
    Operating system: Unix 4.19.0.5
    64-Bit OS: True
    64-Bit Process: True
    User Interactive: True
    Runtime: file:///opt/emby-server/system/System.Private.CoreLib.dll
    Processor count: 1
    Program data path: /var/lib/emby
    Application directory: /opt/emby-server/system
    System.Exception: System.Exception: Invalid username or password
       at Emby.Server.Implementations.Library.DefaultAuthenticationProvider.Authenticate(String username, String password, User resolvedUser)
       at Emby.Server.Implementations.Library.UserManager.AuthenticateWithProvider(IAuthenticationProvider provider, String username, String password, User resolvedUser, CancellationToken cancellationToken)
    Source: Emby.Server.Implementations
    TargetSite: System.Threading.Tasks.Task`1[MediaBrowser.Controller.Authentication.ProviderAuthenticationResult] Authenticate(System.String, System.String, MediaBrowser.Controller.Entities.User)

2019-08-25 18:55:03.470 Info HttpClient: POST https://connect.emby.media/service/user/authenticate
2019-08-25 18:55:03.505 Info UserManager: Authentication request for emby has been denied.
2019-08-25 18:55:03.506 Warn HttpServer: AUTH-ERROR: 192.168.56.102 - Invalid user or password entered.
2019-08-25 18:55:03.506 Error HttpServer: Invalid user or password entered.
2019-08-25 18:55:03.506 Info HttpServer: HTTP Response 401 to 192.168.56.102. Time: 41ms. http://192.168.56.101:8096/emby/Users/authenticatebyname
2019-08-25 18:55:03.841 Info HttpServer: HTTP POST http://192.168.56.101:8096/emby/Users/authenticatebyname. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 18:55:03.845 Error UserManager: Error authenticating with provider Default
    *** Error Report ***
    Version: 4.2.1.0
    Command line: /opt/emby-server/system/EmbyServer.dll -programdata /var/lib/emby -ffdetect /opt/emby-server/bin/ffdetect -ffmpeg /opt/emby-server/bin/ffmpeg -ffprobe /opt/emby-server/bin/ffprobe -restartexitcode 3 -updatepackage emby-server-deb_{version}_amd64.deb
    Operating system: Unix 4.19.0.5
    64-Bit OS: True
    64-Bit Process: True
    User Interactive: True
    Runtime: file:///opt/emby-server/system/System.Private.CoreLib.dll
    Processor count: 1
    Program data path: /var/lib/emby
    Application directory: /opt/emby-server/system
    System.Exception: System.Exception: Invalid username or password
       at Emby.Server.Implementations.Library.DefaultAuthenticationProvider.Authenticate(String username, String password, User resolvedUser)
       at Emby.Server.Implementations.Library.UserManager.AuthenticateWithProvider(IAuthenticationProvider provider, String username, String password, User resolvedUser, CancellationToken cancellationToken)
    Source: Emby.Server.Implementations
    TargetSite: System.Threading.Tasks.Task`1[MediaBrowser.Controller.Authentication.ProviderAuthenticationResult] Authenticate(System.String, System.String, MediaBrowser.Controller.Entities.User)

2019-08-25 18:55:03.845 Info HttpClient: POST https://connect.emby.media/service/user/authenticate
2019-08-25 18:55:03.889 Info UserManager: Authentication request for emby has been denied.
2019-08-25 18:55:03.890 Warn HttpServer: AUTH-ERROR: 192.168.56.102 - Invalid user or password entered.
2019-08-25 18:55:03.890 Error HttpServer: Invalid user or password entered.
2019-08-25 18:55:03.891 Info HttpServer: HTTP Response 401 to 192.168.56.102. Time: 50ms. http://192.168.56.101:8096/emby/Users/authenticatebyname
2019-08-25 18:55:04.280 Info HttpServer: HTTP POST http://192.168.56.101:8096/emby/Users/authenticatebyname. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 18:55:04.284 Error UserManager: Error authenticating with provider Default
    *** Error Report ***
    Version: 4.2.1.0
    Command line: /opt/emby-server/system/EmbyServer.dll -programdata /var/lib/emby -ffdetect /opt/emby-server/bin/ffdetect -ffmpeg /opt/emby-server/bin/ffmpeg -ffprobe /opt/emby-server/bin/ffprobe -restartexitcode 3 -updatepackage emby-server-deb_{version}_amd64.deb
    Operating system: Unix 4.19.0.5
    64-Bit OS: True
    64-Bit Process: True
    User Interactive: True
    Runtime: file:///opt/emby-server/system/System.Private.CoreLib.dll
    Processor count: 1
    Program data path: /var/lib/emby
    Application directory: /opt/emby-server/system
    System.Exception: System.Exception: Invalid username or password
       at Emby.Server.Implementations.Library.DefaultAuthenticationProvider.Authenticate(String username, String password, User resolvedUser)
       at Emby.Server.Implementations.Library.UserManager.AuthenticateWithProvider(IAuthenticationProvider provider, String username, String password, User resolvedUser, CancellationToken cancellationToken)
    Source: Emby.Server.Implementations
    TargetSite: System.Threading.Tasks.Task`1[MediaBrowser.Controller.Authentication.ProviderAuthenticationResult] Authenticate(System.String, System.String, MediaBrowser.Controller.Entities.User)

2019-08-25 18:55:04.284 Info HttpClient: POST https://connect.emby.media/service/user/authenticate
2019-08-25 18:55:04.324 Info UserManager: Authentication request for emby has been denied.
2019-08-25 18:55:04.325 Warn HttpServer: AUTH-ERROR: 192.168.56.102 - Invalid user or password entered.
2019-08-25 18:55:04.325 Error HttpServer: Invalid user or password entered.
2019-08-25 18:55:04.325 Info HttpServer: HTTP Response 401 to 192.168.56.102. Time: 45ms. http://192.168.56.101:8096/emby/Users/authenticatebyname
2019-08-25 18:55:04.784 Info HttpServer: HTTP POST http://192.168.56.101:8096/emby/Users/authenticatebyname. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 18:55:04.786 Error UserManager: Error authenticating with provider Default
    *** Error Report ***
    Version: 4.2.1.0
    Command line: /opt/emby-server/system/EmbyServer.dll -programdata /var/lib/emby -ffdetect /opt/emby-server/bin/ffdetect -ffmpeg /opt/emby-server/bin/ffmpeg -ffprobe /opt/emby-server/bin/ffprobe -restartexitcode 3 -updatepackage emby-server-deb_{version}_amd64.deb
    Operating system: Unix 4.19.0.5
    64-Bit OS: True
    64-Bit Process: True
    User Interactive: True
    Runtime: file:///opt/emby-server/system/System.Private.CoreLib.dll
    Processor count: 1
    Program data path: /var/lib/emby
    Application directory: /opt/emby-server/system
    System.Exception: System.Exception: Invalid username or password
       at Emby.Server.Implementations.Library.DefaultAuthenticationProvider.Authenticate(String username, String password, User resolvedUser)
       at Emby.Server.Implementations.Library.UserManager.AuthenticateWithProvider(IAuthenticationProvider provider, String username, String password, User resolvedUser, CancellationToken cancellationToken)
    Source: Emby.Server.Implementations
    TargetSite: System.Threading.Tasks.Task`1[MediaBrowser.Controller.Authentication.ProviderAuthenticationResult] Authenticate(System.String, System.String, MediaBrowser.Controller.Entities.User)

2019-08-25 18:55:04.788 Info HttpClient: POST https://connect.emby.media/service/user/authenticate
2019-08-25 18:55:04.832 Info UserManager: Authentication request for emby has been denied.
2019-08-25 18:55:04.837 Warn HttpServer: AUTH-ERROR: 192.168.56.102 - Invalid user or password entered.
2019-08-25 18:55:04.837 Error HttpServer: Invalid user or password entered.
2019-08-25 18:55:04.839 Info HttpServer: HTTP Response 401 to 192.168.56.102. Time: 56ms. http://192.168.56.101:8096/emby/Users/authenticatebyname
2019-08-25 18:55:05.351 Info HttpServer: HTTP POST http://192.168.56.101:8096/emby/Users/authenticatebyname. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 18:55:05.353 Info UserManager: Authentication request for emby has succeeded.
2019-08-25 18:55:05.356 Info SessionManager: Creating new access token for user 1
2019-08-25 18:55:05.364 Info HttpServer: HTTP Response 200 to 192.168.56.102. Time: 13ms. http://192.168.56.101:8096/emby/Users/authenticatebyname
2019-08-25 18:55:05.901 Info HttpServer: HTTP POST http://192.168.56.101:8096/emby/Users/authenticatebyname. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 18:55:05.907 Error UserManager: Error authenticating with provider Default
    *** Error Report ***
    Version: 4.2.1.0
    Command line: /opt/emby-server/system/EmbyServer.dll -programdata /var/lib/emby -ffdetect /opt/emby-server/bin/ffdetect -ffmpeg /opt/emby-server/bin/ffmpeg -ffprobe /opt/emby-server/bin/ffprobe -restartexitcode 3 -updatepackage emby-server-deb_{version}_amd64.deb
    Operating system: Unix 4.19.0.5
    64-Bit OS: True
    64-Bit Process: True
    User Interactive: True
    Runtime: file:///opt/emby-server/system/System.Private.CoreLib.dll
    Processor count: 1
    Program data path: /var/lib/emby
    Application directory: /opt/emby-server/system
    System.Exception: System.Exception: Invalid username or password
       at Emby.Server.Implementations.Library.DefaultAuthenticationProvider.Authenticate(String username, String password, User resolvedUser)
       at Emby.Server.Implementations.Library.UserManager.AuthenticateWithProvider(IAuthenticationProvider provider, String username, String password, User resolvedUser, CancellationToken cancellationToken)
    Source: Emby.Server.Implementations
    TargetSite: System.Threading.Tasks.Task`1[MediaBrowser.Controller.Authentication.ProviderAuthenticationResult] Authenticate(System.String, System.String, MediaBrowser.Controller.Entities.User)

2019-08-25 18:55:05.907 Info HttpClient: POST https://connect.emby.media/service/user/authenticate
2019-08-25 18:55:05.945 Info UserManager: Authentication request for emby has been denied.
2019-08-25 18:55:05.945 Warn HttpServer: AUTH-ERROR: 192.168.56.102 - Invalid user or password entered.
2019-08-25 18:55:05.945 Error HttpServer: Invalid user or password entered.
2019-08-25 18:55:05.945 Info HttpServer: HTTP Response 401 to 192.168.56.102. Time: 44ms. http://192.168.56.101:8096/emby/Users/authenticatebyname
2019-08-25 18:55:06.500 Info HttpServer: HTTP POST http://192.168.56.101:8096/emby/Users/authenticatebyname. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 18:55:06.503 Error UserManager: Error authenticating with provider Default
    *** Error Report ***
    Version: 4.2.1.0
    Command line: /opt/emby-server/system/EmbyServer.dll -programdata /var/lib/emby -ffdetect /opt/emby-server/bin/ffdetect -ffmpeg /opt/emby-server/bin/ffmpeg -ffprobe /opt/emby-server/bin/ffprobe -restartexitcode 3 -updatepackage emby-server-deb_{version}_amd64.deb
    Operating system: Unix 4.19.0.5
    64-Bit OS: True
    64-Bit Process: True
    User Interactive: True
    Runtime: file:///opt/emby-server/system/System.Private.CoreLib.dll
    Processor count: 1
    Program data path: /var/lib/emby
    Application directory: /opt/emby-server/system
    System.Exception: System.Exception: Invalid username or password
       at Emby.Server.Implementations.Library.DefaultAuthenticationProvider.Authenticate(String username, String password, User resolvedUser)
       at Emby.Server.Implementations.Library.UserManager.AuthenticateWithProvider(IAuthenticationProvider provider, String username, String password, User resolvedUser, CancellationToken cancellationToken)
    Source: Emby.Server.Implementations
    TargetSite: System.Threading.Tasks.Task`1[MediaBrowser.Controller.Authentication.ProviderAuthenticationResult] Authenticate(System.String, System.String, MediaBrowser.Controller.Entities.User)

2019-08-25 18:55:06.504 Info HttpClient: POST https://connect.emby.media/service/user/authenticate
2019-08-25 18:55:06.546 Info UserManager: Authentication request for emby has been denied.
2019-08-25 18:55:06.547 Warn HttpServer: AUTH-ERROR: 192.168.56.102 - Invalid user or password entered.
2019-08-25 18:55:06.547 Error HttpServer: Invalid user or password entered.
2019-08-25 18:55:06.547 Info HttpServer: HTTP Response 401 to 192.168.56.102. Time: 47ms. http://192.168.56.101:8096/emby/Users/authenticatebyname
2019-08-25 18:55:07.248 Info HttpServer: HTTP POST http://192.168.56.101:8096/emby/Users/authenticatebyname. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 18:55:07.253 Error UserManager: Error authenticating with provider Default
    *** Error Report ***
    Version: 4.2.1.0
    Command line: /opt/emby-server/system/EmbyServer.dll -programdata /var/lib/emby -ffdetect /opt/emby-server/bin/ffdetect -ffmpeg /opt/emby-server/bin/ffmpeg -ffprobe /opt/emby-server/bin/ffprobe -restartexitcode 3 -updatepackage emby-server-deb_{version}_amd64.deb
    Operating system: Unix 4.19.0.5
    64-Bit OS: True
    64-Bit Process: True
    User Interactive: True
    Runtime: file:///opt/emby-server/system/System.Private.CoreLib.dll
    Processor count: 1
    Program data path: /var/lib/emby
    Application directory: /opt/emby-server/system
    System.Exception: System.Exception: Invalid username or password
       at Emby.Server.Implementations.Library.DefaultAuthenticationProvider.Authenticate(String username, String password, User resolvedUser)
       at Emby.Server.Implementations.Library.UserManager.AuthenticateWithProvider(IAuthenticationProvider provider, String username, String password, User resolvedUser, CancellationToken cancellationToken)
    Source: Emby.Server.Implementations
    TargetSite: System.Threading.Tasks.Task`1[MediaBrowser.Controller.Authentication.ProviderAuthenticationResult] Authenticate(System.String, System.String, MediaBrowser.Controller.Entities.User)

2019-08-25 18:55:07.253 Info HttpClient: POST https://connect.emby.media/service/user/authenticate
2019-08-25 18:55:07.295 Info UserManager: Authentication request for emby has been denied.
2019-08-25 18:55:07.296 Warn HttpServer: AUTH-ERROR: 192.168.56.102 - Invalid user or password entered.
2019-08-25 18:55:07.296 Error HttpServer: Invalid user or password entered.
2019-08-25 18:55:07.297 Info HttpServer: HTTP Response 401 to 192.168.56.102. Time: 48ms. http://192.168.56.101:8096/emby/Users/authenticatebyname
2019-08-25 18:55:08.054 Info HttpServer: HTTP POST http://192.168.56.101:8096/emby/Users/authenticatebyname. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 18:55:08.057 Error UserManager: Error authenticating with provider Default
    *** Error Report ***
    Version: 4.2.1.0
    Command line: /opt/emby-server/system/EmbyServer.dll -programdata /var/lib/emby -ffdetect /opt/emby-server/bin/ffdetect -ffmpeg /opt/emby-server/bin/ffmpeg -ffprobe /opt/emby-server/bin/ffprobe -restartexitcode 3 -updatepackage emby-server-deb_{version}_amd64.deb
    Operating system: Unix 4.19.0.5
    64-Bit OS: True
    64-Bit Process: True
    User Interactive: True
    Runtime: file:///opt/emby-server/system/System.Private.CoreLib.dll
    Processor count: 1
    Program data path: /var/lib/emby
    Application directory: /opt/emby-server/system
    System.Exception: System.Exception: Invalid username or password
       at Emby.Server.Implementations.Library.DefaultAuthenticationProvider.Authenticate(String username, String password, User resolvedUser)
       at Emby.Server.Implementations.Library.UserManager.AuthenticateWithProvider(IAuthenticationProvider provider, String username, String password, User resolvedUser, CancellationToken cancellationToken)
    Source: Emby.Server.Implementations
    TargetSite: System.Threading.Tasks.Task`1[MediaBrowser.Controller.Authentication.ProviderAuthenticationResult] Authenticate(System.String, System.String, MediaBrowser.Controller.Entities.User)

2019-08-25 18:55:08.057 Info HttpClient: POST https://connect.emby.media/service/user/authenticate
2019-08-25 18:55:08.094 Info UserManager: Authentication request for emby has been denied.
2019-08-25 18:55:08.095 Warn HttpServer: AUTH-ERROR: 192.168.56.102 - Invalid user or password entered.
2019-08-25 18:55:08.095 Error HttpServer: Invalid user or password entered.
2019-08-25 18:55:08.095 Info HttpServer: HTTP Response 401 to 192.168.56.102. Time: 41ms. http://192.168.56.101:8096/emby/Users/authenticatebyname
2019-08-25 18:55:08.925 Info HttpServer: HTTP POST http://192.168.56.101:8096/emby/Users/authenticatebyname. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 18:55:08.926 Error UserManager: Error authenticating with provider Default
    *** Error Report ***
    Version: 4.2.1.0
    Command line: /opt/emby-server/system/EmbyServer.dll -programdata /var/lib/emby -ffdetect /opt/emby-server/bin/ffdetect -ffmpeg /opt/emby-server/bin/ffmpeg -ffprobe /opt/emby-server/bin/ffprobe -restartexitcode 3 -updatepackage emby-server-deb_{version}_amd64.deb
    Operating system: Unix 4.19.0.5
    64-Bit OS: True
    64-Bit Process: True
    User Interactive: True
    Runtime: file:///opt/emby-server/system/System.Private.CoreLib.dll
    Processor count: 1
    Program data path: /var/lib/emby
    Application directory: /opt/emby-server/system
    System.Exception: System.Exception: Invalid username or password
       at Emby.Server.Implementations.Library.DefaultAuthenticationProvider.Authenticate(String username, String password, User resolvedUser)
       at Emby.Server.Implementations.Library.UserManager.AuthenticateWithProvider(IAuthenticationProvider provider, String username, String password, User resolvedUser, CancellationToken cancellationToken)
    Source: Emby.Server.Implementations
    TargetSite: System.Threading.Tasks.Task`1[MediaBrowser.Controller.Authentication.ProviderAuthenticationResult] Authenticate(System.String, System.String, MediaBrowser.Controller.Entities.User)

2019-08-25 18:55:08.926 Info HttpClient: POST https://connect.emby.media/service/user/authenticate
2019-08-25 18:55:08.968 Info UserManager: Authentication request for emby has been denied.
2019-08-25 18:55:08.969 Warn HttpServer: AUTH-ERROR: 192.168.56.102 - Invalid user or password entered.
2019-08-25 18:55:08.969 Error HttpServer: Invalid user or password entered.
2019-08-25 18:55:08.969 Info HttpServer: HTTP Response 401 to 192.168.56.102. Time: 44ms. http://192.168.56.101:8096/emby/Users/authenticatebyname
2019-08-25 18:55:09.861 Info HttpServer: HTTP POST http://192.168.56.101:8096/emby/Users/authenticatebyname. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 18:55:09.865 Error UserManager: Error authenticating with provider Default
    *** Error Report ***
    Version: 4.2.1.0
    Command line: /opt/emby-server/system/EmbyServer.dll -programdata /var/lib/emby -ffdetect /opt/emby-server/bin/ffdetect -ffmpeg /opt/emby-server/bin/ffmpeg -ffprobe /opt/emby-server/bin/ffprobe -restartexitcode 3 -updatepackage emby-server-deb_{version}_amd64.deb
    Operating system: Unix 4.19.0.5
    64-Bit OS: True
    64-Bit Process: True
    User Interactive: True
    Runtime: file:///opt/emby-server/system/System.Private.CoreLib.dll
    Processor count: 1
    Program data path: /var/lib/emby
    Application directory: /opt/emby-server/system
    System.Exception: System.Exception: Invalid username or password
       at Emby.Server.Implementations.Library.DefaultAuthenticationProvider.Authenticate(String username, String password, User resolvedUser)
       at Emby.Server.Implementations.Library.UserManager.AuthenticateWithProvider(IAuthenticationProvider provider, String username, String password, User resolvedUser, CancellationToken cancellationToken)
    Source: Emby.Server.Implementations
    TargetSite: System.Threading.Tasks.Task`1[MediaBrowser.Controller.Authentication.ProviderAuthenticationResult] Authenticate(System.String, System.String, MediaBrowser.Controller.Entities.User)

2019-08-25 18:55:09.865 Info HttpClient: POST https://connect.emby.media/service/user/authenticate
2019-08-25 18:55:09.905 Info UserManager: Authentication request for emby has been denied.
2019-08-25 18:55:09.908 Warn HttpServer: AUTH-ERROR: 192.168.56.102 - Invalid user or password entered.
2019-08-25 18:55:09.908 Error HttpServer: Invalid user or password entered.
2019-08-25 18:55:09.914 Info HttpServer: HTTP Response 401 to 192.168.56.102. Time: 54ms. http://192.168.56.101:8096/emby/Users/authenticatebyname
2019-08-25 18:55:10.861 Info HttpServer: HTTP POST http://192.168.56.101:8096/emby/Users/authenticatebyname. UserAgent: Mozilla/5.0 (X11; Linux x86_64; rv:60.0) Gecko/20100101 Firefox/60.0
2019-08-25 18:55:10.864 Error UserManager: Error authenticating with provider Default
    *** Error Report ***
    Version: 4.2.1.0
    Command line: /opt/emby-server/system/EmbyServer.dll -programdata /var/lib/emby -ffdetect /opt/emby-server/bin/ffdetect -ffmpeg /opt/emby-server/bin/ffmpeg -ffprobe /opt/emby-server/bin/ffprobe -restartexitcode 3 -updatepackage emby-server-deb_{version}_amd64.deb
    Operating system: Unix 4.19.0.5
    64-Bit OS: True
    64-Bit Process: True
    User Interactive: True
    Runtime: file:///opt/emby-server/system/System.Private.CoreLib.dll
    Processor count: 1
    Program data path: /var/lib/emby
    Application directory: /opt/emby-server/system
    System.Exception: System.Exception: Invalid username or password
       at Emby.Server.Implementations.Library.DefaultAuthenticationProvider.Authenticate(String username, String password, User resolvedUser)
       at Emby.Server.Implementations.Library.UserManager.AuthenticateWithProvider(IAuthenticationProvider provider, String username, String password, User resolvedUser, CancellationToken cancellationToken)
    Source: Emby.Server.Implementations
    TargetSite: System.Threading.Tasks.Task`1[MediaBrowser.Controller.Authentication.ProviderAuthenticationResult] Authenticate(System.String, System.String, MediaBrowser.Controller.Entities.User)

2019-08-25 18:55:10.864 Info HttpClient: POST https://connect.emby.media/service/user/authenticate
2019-08-25 18:55:10.901 Info UserManager: Authentication request for emby has been denied.
2019-08-25 18:55:10.902 Warn HttpServer: AUTH-ERROR: 192.168.56.102 - Invalid user or password entered.
2019-08-25 18:55:10.902 Error HttpServer: Invalid user or password entered.
2019-08-25 18:55:10.903 Info HttpServer: HTTP Response 401 to 192.168.56.102. Time: 43ms. http://192.168.56.101:8096/emby/Users/authenticatebyname
```
