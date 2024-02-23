onCreate() - entry point for android apps
@Composable 
- tells jetpack compose to generate UI
- void 
@Preview
- tells AndroidStudio to render in preview window
Surface - container that you can modify colors, borders, text
Modifier - agument or decerate a @Composable
- dp - density-independant pixels, unit for Material UI 3
var blah by remember { mutableStateOf() }
- remember alowsy recomposition
