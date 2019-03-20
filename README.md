# Conversational AI Design Guidance


## Welcome Experience

| UI Screenshot | Code Samples |
|----|----|
| ![Adaptive Card Image](images/welcomemessage.png) | C# sample: [Welcome Message][3] |

## Bot Typing Experience
| UI Screenshot | Code Samples |
|----|----|
| ![](images/TypingActivity.png) | C# sample: [Send Typing Activity][10] |


## Prompts


### Text Prompt
Asks for general text input.

| UI Screenshot | Code Samples |
|----|----|
| ![](images/SimplePrompt.png) | C# sample: [Simple Prompt][4] |


### Number Prompt
Asks for a number.
| UI Screenshot | Code Samples |
|----|----|
| ![](images/number-prompt.png) | C# sample:  |

### DateTime Prompt
Asks for a date-time.

| UI Screenshot | Code Samples |
|----|----|
| ![](images/datetime-prompt.png) | C# sample:  |

### Choice Prompt
Asks for a choice from a set of options.

### Confirm Prompt
Asks for a confirmation.

### Attachment Prompt
Asks for one or more attachments, such as a document or image.

### Simple Prompt
| UI Screenshot | Code Samples |
|----|----|
| ![Adaptive Card Image](images/SimplePrompt.png) | C# sample: [Simple Prompt][4] |

### Multi Prompt
| UI Screenshot | Code Samples |
|----|----|
| ![Adaptive Card Image](images/MultiplePrompt.png) | C# sample: [Multi-Turn Prompt][5] |

### Validation Prompt
| UI Screenshot | Code Samples |
|----|----|
| ![](images/validation-prompt.png) | C# sample: [Validation Prompt][12] |



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
| ![](images/animationcard.png) | C# sample: [Using Cards][2] |

### AudioCard
| UI Screenshot | Code Samples |
|----|----|
| ![](images/audiocard.png) | C# sample: [Using Cards][2] |

### Hero Card
| UI Screenshot | Code Samples |
|----|----|
| ![](images/herocard.png) | C# sample: [Using Cards][2] |

### ThumbnailCard
| UI Screenshot | Code Samples |
|----|----|
| ![](images/thumbnailcardalt.png) | C# sample: [Using Cards][2] |

### RecieptCard
| UI Screenshot | Code Samples |
|----|----|
| ![](images/.png) | C# sample: [Using Cards][2] |

### SignInCard
| UI Screenshot | Code Samples |
|----|----|
| ![](images/signincard.png) | C# sample: [Using Cards][2] |


### VideoCard
| UI Screenshot | Code Samples |
|----|----|
| ![](images/Videocard.png) | C# sample: [Using Cards][2] |

### CardCarousel
| UI Screenshot | Code Samples |
|----|----|
| ![](images/CarouselCard.png) | C# sample: [Using Cards][2] |

### Card List
| UI Screenshot | Code Samples |
|----|----|
| ![](images/ListCard.png) | C# sample: [Using Cards][2] |



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


## Nested Conversation Dialogs
Nested Conversation Dialogs | Code Sample|
-------------------------|-----------|
![](images/DonateDialog.gif)  | C# sample: [MenuBot C#][8] <br/> JS sample: [MenuBot JS][9]

Enjoy.

[1]: https://github.com/Microsoft/BotBuilder-Samples/tree/master/samples/csharp_dotnetcore/07.using-adaptive-cards
[2]: https://github.com/Microsoft/BotBuilder-Samples/tree/master/samples/csharp_dotnetcore/06.using-cards
[3]: https://github.com/Microsoft/BotBuilder-Samples/blob/master/samples/csharp_dotnetcore/03.welcome-user
[4]: https://github.com/Microsoft/BotBuilder-Samples/blob/master/samples/csharp_dotnetcore/04.simple-prompt
[5]: https://github.com/Microsoft/BotBuilder-Samples/blob/master/samples/csharp_dotnetcore/05.multi-turn-prompt
[6]: https://github.com/Microsoft/BotBuilder-Samples/blob/master/samples/csharp_dotnetcore/08.suggested-actions
[7]: https://github.com/ikivanc/Digital-Travel-Assistant
[8]: https://github.com/ikivanc/menu-bot/tree/master/csharp_dotnetcore
[9]: https://github.com/ikivanc/menu-bot/tree/master/javascript_nodejs
[10]: https://gist.github.com/ikivanc/697d6c38871819b8b31e4bbc481f24c9
[11]: https://github.com/Microsoft/BotBuilder-Samples/tree/master/samples/csharp_dotnetcore/10.prompt-validations
[12]: https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-prompts?view=azure-bot-service-4.0&tabs=csharp#custom-validation