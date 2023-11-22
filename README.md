# wprowadzenieC-

<Window x:Class="wprowadzeni3psr.Window2"
        xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
        xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
        xmlns:d="http://schemas.microsoft.com/expression/blend/2008"
        xmlns:mc="http://schemas.openxmlformats.org/markup-compatibility/2006"
        xmlns:local="clr-namespace:wprowadzeni3psr"
        mc:Ignorable="d"
        Title="Window2" Height="450" Width="800">
    <DockPanel>
        <Button DockPanel.Dock="Top">1</Button>
        <Button DockPanel.Dock="Right">2</Button>
        <Button DockPanel.Dock="Left">3</Button>
        <Grid>
            <Grid.ColumnDefinitions>
                <ColumnDefinition Width="*"></ColumnDefinition>
                <ColumnDefinition Width="*"></ColumnDefinition>
            </Grid.ColumnDefinitions>
            <Grid.RowDefinitions>
                <RowDefinition Height="*"></RowDefinition>
                <RowDefinition Height="*"></RowDefinition>
            </Grid.RowDefinitions>
            <UniformGrid Grid.Column="0" Grid.Row="0" Rows="2">
                <Button>4</Button>
                <Button>5</Button>
                <Button>6</Button>
                <Button>7</Button>
                <Button>8</Button>
                <Button>9</Button>
                <Button>10</Button>
                <Button>11</Button>
            </UniformGrid>
            <StackPanel Grid.Column="1" Grid.Row="0">
                <Button Height="30">12</Button>
                <Button Height="30">13</Button>
                <Button Height="30">14</Button>
            </StackPanel>
            <DockPanel Grid.Column="1" Grid.Row="1">
                <Button>15</Button>
            </DockPanel>
            <DockPanel Grid.Column="0" Grid.Row="1">
                <Button Width="30">16</Button>
                <Button Width="30">17</Button>
                <Button>18</Button>
            </DockPanel>
            
        </Grid>
    </DockPanel>
</Window>
