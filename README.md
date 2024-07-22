Este proyecto está basado en el tutorial https://www.youtube.com/watch?v=YQ1EJJZBHyE&list=PLVO9NeuU9l9zAYPg5DhJYfVjJ8RYqQ0FC de Abel Dutra UI: https://github.com/Abel13/NavigationDrawer/tree/master/NavigationDrawerPopUpMenu2

Paquetes NuGet instalados: MaterialDesignThemes y MaterialDesignColors

En App.xaml se usan estos 4 recursos, de los cuales, el 3 y 4 ya no existen más:
    <ResourceDictionary Source="pack://application:,,,/MaterialDesignThemes.Wpf;component/Themes/MaterialDesignTheme.Light.xaml" />
    <ResourceDictionary Source="pack://application:,,,/MaterialDesignThemes.Wpf;component/Themes/MaterialDesignTheme.Defaults.xaml" />
    <ResourceDictionary Source="pack://application:,,,/MaterialDesignColors;component/Themes/Recommended/Primary/MaterialDesignColor.Blue.xaml" />
    <ResourceDictionary Source="pack://application:,,,/MaterialDesignColors;component/Themes/Recommended/Accent/MaterialDesignColor.Indigo.xaml" />
Por lo que el estilo MaterialDesignFloatingActionMiniAccentButton usado en los botones devuelve error. Simplemente se deja de usar el recurso.
