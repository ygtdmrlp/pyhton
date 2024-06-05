QApplication sınıfının quitOnLastWindowClosed özelliğini kullanabiliriz. Bu özellik, 
tüm pencerelerin kapatılması durumunda uygulamanın kapatılıp kapatılmayacağını kontrol eder. Varsayılan olarak bu özellik True olarak ayarlıdır, 
yani tüm pencereler kapatıldığında uygulama otomatik olarak kapanır. 
Ancak setQuitOnLastWindowClosed(False) kullanarak bu özelliği False olarak ayarlayabiliriz. İşte güncellenmiş kod:
