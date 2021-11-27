<p align="center">
	<a href="https://github.com/tenhobi/effective_dart"><img src="https://img.shields.io/badge/style-effective_dart-40c4ff.svg" alt="Effective Dart Badge"></a>
	<a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/license-MIT-purple.svg" alt="MIT License Badge"></a>
</p>

</p>
<p align = "center">
<!-- <a href="https://pub.dev/packages/scaled_list"> Pub.dev</a> -->
</p>


# Scaled List
Custom bottom navigation bar with diamond icon in the middle you can customize the number of items either be Five or three.


<p align="center">
	<img src="https://i.imgur.com/a40bkMu.png" alt="Image" height="500"/>
	<img src="https://i.imgur.com/uB58pWN.png" alt="Image" height="500"/>
	
	

## Usage

```dart
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Diamond Bottom Bar',
      theme: ThemeData(
        primarySwatch: Colors.blue,
      ),
      home: Scaffold(
        body: _selectedWidget,
        bottomNavigationBar: DiamondBottomNavigation(
          itemIcons: const [
            Icons.home,
            Icons.notifications,
            Icons.message,
            Icons.account_box,
          ],
          centerIcon: Icons.place,
          selectedIndex: _selectedIndex,
          onItemPressed: onPressed,
        ),
      ),
    );
  }
  ```
  
## Usage Scenarios
- When You like to use Bottom navigation with Main Center Item in a diamong shape.

## Contributers
<a href="https://github.com/hosain-mohamed"> Hosain Mohamed</a>

## Inspiration
- <a href="https://dribbble.com/shots15332641-Medical-Mobile-App">Imran Hossen</a>
