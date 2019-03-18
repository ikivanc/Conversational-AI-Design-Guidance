# Conversational AI Design Guidance


## Welcome Experience

| UI Screenshot | Code Samples |
|----|----|
| ![Adaptive Card Image](images/welcomemessage.png) | C# sample: [Welcome Message][3] |

## Bot Typing Experience
| UI Screenshot | Code Samples |
|----|----|
| ![Adaptive Card Image](images/welcomemessage.png) | C# sample: [Welcome Message][3] |


## Prompts
### Simple Prompt
| UI Screenshot | Code Samples |
|----|----|
| ![Adaptive Card Image](images/welcomemessage.png) | C# sample: [Simple Prompt][4] |

### Multi Prompt
| UI Screenshot | Code Samples |
|----|----|
| ![Adaptive Card Image](images/welcomemessage.png) | C# sample: [Multi-Turn Prompt][5] |

### Text Prompt
### DateTime Prompt
### Choice Prompt
### Confirm Prompt


## Suggested Action
| UI Screenshot | Code Samples |
|----|----|
| ![Adaptive Card Image](images/SuggestedCard.png) | C# sample: [Suggested Action][6] |


## AdaptiveCard
An open card exchange format rendered as a JSON object. Typically used for cross-channel deployment of cards. Cards adapt to the look and feel of each host channel.

| UI Screenshot | Code Samples |
|----|----|
| ![Adaptive Card Image](images/adaptivecard.png) | C# sample: [Using Adaptive Cards][1] |

## Cards
### AnimationCard
A card that can play animated GIFs or short videos.

| UI Screenshot | Code Samples |
|----|----|
| ![](images/thumbnailcard.png) | C# sample: [Using Cards][2] |

### AudioCard
| UI Screenshot | Code Samples |
|----|----|
| ![](images/thumbnailcard.png) | C# sample: [Using Cards][2] |

### Hero Card
| UI Screenshot | Code Samples |
|----|----|
| ![](images/herocard.png) | C# sample: [Using Cards][2] |

### ThumbnailCard
| UI Screenshot | Code Samples |
|----|----|
| ![](images/thumbnailcard.png) | C# sample: [Using Cards][2] |

### RecieptCard
| UI Screenshot | Code Samples |
|----|----|
| ![](images/thumbnailcard.png) | C# sample: [Using Cards][2] |

### SignInCard
| UI Screenshot | Code Samples |
|----|----|
| ![](images/thumbnailcard.png) | C# sample: [Using Cards][2] |


### VideoCard
| UI Screenshot | Code Samples |
|----|----|
| ![](images/thumbnailcard.png) | C# sample: [Using Cards][2] |

### CardCarousel
| UI Screenshot | Code Samples |
|----|----|
| ![](images/thumbnailcard.png) | C# sample: [Using Cards][2] |

### Card List
| UI Screenshot | Code Samples |
|----|----|
| ![](images/thumbnailcard.png) | C# sample: [Using Cards][2] |



# Conversation User Experiences

## Natural Language Processing

LUIS

## Question and Answering

QnAMaker

## Search

Azure Search

## Authentication

Authentication


## Dialogs


## Guided Conversation Experience
Guided Conversation | Code Sample|
:-------------------------:|:-----------:|
![](images/dialog.png)  | C# sample: [Digital Travel Assistant][7]

## LUIS + Guided Conversation Experience
Guided Conversation | Code Sample|
:-------------------------:|:-----------:|
![](images/luisdialog1.png)  | C# sample: [Digital Travel Assistant][7]


## LUIS Experience
Dynamic Conversations with multiple inputs managed in WaterFall Dialogs to provide only needed prompts to retrieve information.
On the left side , a question including "number of guests", "Region" , "Check-in Date" and "Check-out Date", then agent asks only needed questions. 
On the right side, the question includes only "number of guests" and "Region" and then agent ask questions to complete them.

 LUIS with 4 entities             |  LUIS with 2 entities | Code Sample|
:-------------------------:|:-------------------------:|:-----------:|
![](images/luisdialog.png)  |  ![](images/luisdialog2.png) | C# sample: [Digital Travel Assistant][7]



[1]: https://github.com/Microsoft/BotBuilder-Samples/tree/master/samples/csharp_dotnetcore/07.using-adaptive-cards
[2]: https://github.com/Microsoft/BotBuilder-Samples/tree/master/samples/csharp_dotnetcore/06.using-cards
[3]: https://github.com/Microsoft/BotBuilder-Samples/blob/master/samples/csharp_dotnetcore/03.welcome-user
[4]: https://github.com/Microsoft/BotBuilder-Samples/blob/master/samples/csharp_dotnetcore/04.simple-prompt
[5]: https://github.com/Microsoft/BotBuilder-Samples/blob/master/samples/csharp_dotnetcore/05.multi-turn-prompt
[6]: https://github.com/Microsoft/BotBuilder-Samples/blob/master/samples/csharp_dotnetcore/08.suggested-actions
[7]: https://github.com/ikivanc/Digital-Travel-Assistant