# kgps_locator_mayralima

A new Flutter project.

# Métodos que retornam Widget
Foram identificados 7 métodos que retornam Widget no projeto:

1. build() – KGpsLocatorApp: utiliza MaterialApp, ThemeData e ColorScheme para configurar a estrutura, o tema e a tela inicial da aplicação.

2. build() – _HomePageState: utiliza Scaffold, AppBar, SafeArea, Column, SizedBox, Expanded, Padding e botões para montar a interface principal.

3. _buildLocationInfo(): utiliza Padding, EdgeInsets.symmetric, Card e Column para apresentar latitude, longitude e altitude.

4. _buildNavigationInfo(): utiliza Card, Padding, Column, Text e SizedBox para apresentar as informações do waypoint selecionado.

5. _buildWaypointList(): utiliza ListView.builder, Dismissible, Container, ListTile, Icon e Text para criar a lista de waypoints e permitir interações de deslizar e pressionar.

6. _infoRow(): utiliza Padding, Row, MainAxisAlignment.spaceBetween e Text para organizar as informações em linhas.

7. build() – Compass: utiliza SizedBox e CustomPaint para definir o tamanho da bússola e chamar a classe CompassPainter, responsável pelo desenho personalizado.

Observação: os componentes foram analisados com auxílio de IA para compreender suas finalidades e como contribuem para a construção da interface Flutter.