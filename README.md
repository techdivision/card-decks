# Welcome to the Card family!
<img width="50" src="https://github.com/techdivision/card-documentation-assets/raw/master/assets/Logo.png" alt="" />

Available Card Packages  
[Card - the basics](https://github.com/techdivision/card)  
[Card decks - aggregate cards beautifully](https://github.com/techdivision/card-decks)      
[Card shuffle - deck filtering](https://github.com/techdivision/card-shuffle)      
[Bootstrap 4 styling for cards](https://github.com/techdivision/card-bootstrap4)        
[Materialize styling for cards](https://github.com/techdivision/card-materialize)  

# TechDivision.Card.Decks - Organize your cards!
> Use this package if you
> - want cards and decks
> - know how to apply css classes and styling on your own  

TechDivision.Card.Decks raises the reusability and offers various options to organize your cards 
 
## For editors
This package brings three document decks (automatic) and one content card deck (manual) who allows you to aggregate cards beautifully.
Some minimal styling is added, so that you can use it out of the box.

#### Deck with content cards (manual)
Insert document or content cards to create your own individual deck
![SelectedNodes](https://github.com/techdivision/card-documentation-assets/raw/master/assets/card-decks/ContentCards.gif)
#### Deck with child nodes (automatic)
Select a parent node and the deck will render its direct child documents.
![SelectedNodes](https://github.com/techdivision/card-documentation-assets/raw/master/assets/card-decks/ChildNodes.gif)
#### Deck with specific NodeTypes (automatic)
Select one or more specific NodeTypes and the deck will render each of those nodes.
Comes in handy for things like JobPostings etc.
![SelectedNodes](https://github.com/techdivision/card-documentation-assets/raw/master/assets/card-decks/NodeTypes.gif)
#### Deck with selected nodes (automatic)
Select desired document nodes to be displayed as cards.
![SelectedNodes](https://github.com/techdivision/card-documentation-assets/raw/master/assets/card-decks/SelectedNodes.gif)

## For Developers

### Installation

TechDivision.Card.Decks is available via packagist. Add `"techdivision/card-decks" : "~1.0"` to the require section of the composer.json
or run `composer require techdivision/card-decks`.  
**This package also installs [TechDivision.Card](https://github.com/techdivision/card)**

### Configuration
TechDivision.Card.Decks runs out of the box.  
In order to remove the default stylesheet, please do the following:  

```
prototype(Neos.Neos:Page) {
    head.stylesheets.cardGrid >
}
```

### Contribution
We will be happy to receive pull requests - dont hesitate!