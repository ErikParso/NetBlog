```csharp
[assembly: XamlCompilation(XamlCompilationOptions.Compile)]
namespace XamarinFormsClient
{
    public partial class App : Application
    {
        public App()
        {
            InitializeComponent();

            MainPage = new MainPage();
        }

        protected override void OnStart()
        {
            // Handle when your app starts
        }

        protected override void OnSleep()
        {
            // Handle when your app sleeps
        }

        protected override void OnResume()
        {
            // Handle when your app resumes
        }
    }
}
```

```xaml
<ContentPage.Content>
    <StackLayout>
        <Button Text="Login" x:Name="Login" />
        <Button Text="Call Api" x:Name="CallApi" />
        <Label x:Name="OutputText"
            VerticalOptions="FillAndExpand"
            HorizontalOptions="FillAndExpand" />
    </StackLayout>
</ContentPage.Content>
```
