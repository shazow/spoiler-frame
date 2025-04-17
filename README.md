# Spoiler Inside - Farcaster mini app

<img width="214" alt="image" src="https://github.com/user-attachments/assets/30841bba-dc28-4239-86ea-0458ff12796d" />
<img width="214" alt="image" src="https://github.com/user-attachments/assets/6056ed3e-28c4-451a-b3d6-a34123d1cea8" />

## Lore

I originally built a minimal version myself, but then used AI to one-shot a better version real quick, then spent way more time fixing up the result. 🙃

Initial prompt for Claude Sonnet 3.7:

> Make me a plain single-page javascript app named "Spoiler Frame" which takes two inputs:
> 1. the spoiler body (placeholder: "Darth Vader is Luke's father") 
> 2. a warning to show before the spoiler (placeholder: "Star Wars: Episode V - The Empire Strikes Back")
>
> When submitted, it encodes the two fields in base64 in the URL after # to avoid refreshing.
>
> If the app is loaded with the fields present in the URL, it decodes it and presents a prompt with the warning to reveal the spoiler. If clicked, it reveals it.
>
> If the variables aren't present in the URL, then it shows the inputs to create a spoiler warning.


## License

MIT
