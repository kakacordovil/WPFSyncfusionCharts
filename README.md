# WPFSyncfusionCharts

[Getting Started with the WPF Charts of Syncfusion](https://www.youtube.com/watch?v=5b8nEevQPC8&t=32s)

- Create the project WPF
- Install the Nuget Syncfusion.SfChart.WPF
- Add the attribute to the Window tag on the MainWindow.xaml file: xmlns:chart="clr-namespace:Syncfusion.UI.Xaml.Charts;assembly=Syncfusion.SfChart.WPF", like the example below:

        <Window x:Class="WpfChartDemo.MainWindow"
        xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
        xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
        xmlns:d="http://schemas.microsoft.com/expression/blend/2008"
        xmlns:mc="http://schemas.openxmlformats.org/markup-compatibility/2006"
        xmlns:chart="clr-namespace:Syncfusion.UI.Xaml.Charts;assembly=Syncfusion.SfChart.WPF"
        xmlns:local="clr-namespace:WpfChartDemo"
        mc:Ignorable="d"
        Title="MainWindow" Height="450" Width="800" >
