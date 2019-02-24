<template>
  <div class='about'>
    <h1 class='title'>About</h1>
    <div class='about-text'>
      <p >He says he's the property of Obi-Wan Kenobi, a resident of these parts. And it's a private message for him. Quite frankly, sir I don't know what he's talking about. Our last master was Captain Antilles, but with what we've been through, this little R2 unit has become a bit eccentric. Obi-Wan Kenobi? I wonder if he means old Ben Kenobi? I beg your pardon, sir, but do you know what he's talking about? Well, I don't know anyone named Obi-Wan, but old Ben lives out beyond the dune sea. He's kind of a strange old hermit. I wonder who she is. It sounds like she's in trouble. I'd better play back the whole thing.</p>
      <p>Remember, a Jedi can feel the Force flowing through him. You mean it controls your actions? Partially. But it also obeys your commands. Hokey religions and ancient weapons are no match for a good blaster at your side, kid. You don't believe in the Force, do you? Kid, I've flown from one side of this galaxy to the other. I've seen a lot of strange stuff, but I've never seen anything to make me believe there's one all-powerful force controlling everything. There's no mystical energy field that controls my destiny. It's all a lot of simple tricks and nonsense. I suggest you try it again, Luke. This time, let go your conscious self and act on instinct. With the blast shield down, I can't even see. How am I supposed to fight? Your eyes can deceive you. Don't trust them.
      Lock the door, Artoo. All right, check that side of the street. It's secure. Move on to the next door. I would much rather have gone with Master Luke than stay here with you. I don't know what all the trouble is about, but I'm sure it must be your fault. You watch your language!</p>
      <p>And what of the Rebellion? If the Rebels have obtained a complete technical readout of this station, it is possible, however unlikely, that they might find a weakness and exploit it. The plans you refer to will soon be back in our hands. Any attack made by the Rebels against this station would be a useless gesture, no matter what technical data they've obtained. This station is now the ultimate power in the universe. I suggest we use it!</p>
      <p>It looks like an Imperial cruiser. Our passengers must be hotter than I thought. Try and hold them off. Angle the deflector shield while I make the calculations for the jump to light speed. Stay sharp! There are two more coming in, they're going to try to cut us off. Why don't you outrun them? I thought you said this thing was fast. Watch your mouth, kid, or you're going to find yourself floating home. We'll be safe enough once we make the jump to hyperspace. Besides, I know a few maneuvers. We'll lose them! Here's where the fun begins!</p>
      <p>Take over! See to him! Look there! They're madmen! They're heading for the prison level. If you hurry, you might catch them. Follow me! You stand guard. Come on! Oh! All this excitement has overrun the circuits of my counterpart here. If you don't mind, I'd like to take him down to maintenance. All right.</p>
    </div>
    <img class='portrait' src='https://www.gannett-cdn.com/-mm-/d066f30dc5f5a4d6880226230c91c9bcd6c679e1/c=3-0-453-600/local/-/media/Phoenix/GenericImages/2014/04/23//1398281185000-Cedric-Charles-Jordan.jpg?width=534&height=712&fit=crop' alt='photo of jordan standley'>
  </div>
</template>

<script>
export default {
  
}
</script>

<style scoped>
  .about {
    margin: 10vh 0 0 0;
    display: grid;
    height: 100vh;
    overflow: scroll;
    grid-template-columns: 10vw 20vw 20vw 20vw 20vw 10vw;
  }
  .title {
    grid-column-start: 2;
  }
  .about-text {
    grid-column-start: 2;
    grid-column-end: 4;
  }
  .portrait {
    width: 20vw;
    grid-column-start: 5;
    grid-column-end: 6;
  }
</style>
