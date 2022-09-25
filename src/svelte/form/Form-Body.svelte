<div class="form-body">
    <div class="form-row">
      <div class="input-container">
        <label for="first-name">First Name</label>
        <input type="text" name="first-name" id="first-name" placeholder="John" required/>
      </div>
      <div class="input-container">
        <label for="last-name">Last Name</label>
        <input type="text" name="last-name" id="last-name" placeholder="Doe" required/>
      </div>
    </div>
    <div class="form-row">
      <div class="input-container">
        <label for="user-mail">Email</label>
        <input type="text" name="user-mail" id="user-mail" placeholder="john.doe@mail.com" required/>
      </div>
      <div class="input-container">
        <label for="user-phone">Phone Number</label>
        <input type="tel" name="user-phone" id="user-phone" pattern="[0-9]{3}-[0-9]{3}-[0-9]{4}" placeholder="(123) 456-7890" required/>
      </div>
    </div>
    <div class="form-row">
      <div class="input-container">
        <label for="user-password">Password</label>
        <input type="password" name="user-password" id="user-password" required/>
      </div>
      <div class="input-container">
        <label for="confirmed-password">Confirm Password</label>
        <input type="password" name="" id="confirmed-password" required/>
      </div>
    </div>
</div>

<style lang="scss">

  .form-body {
      display: flex;
      flex-direction: column;
      gap: 2rem;
  }

    .form-row {
        display: flex;
        gap: 6rem;
    }

    .input-container {
        display: flex;
        flex-direction: column;
    }

    label {
        font-size: 1.8rem;
        margin-bottom: 0.5rem;
        margin-left: 0.5rem;
    }

    input {
        width: 20rem;
        padding: 0.8rem 1rem;
        border-radius: .45rem;
        border: solid .2rem var(--une-light-grey);
    }
</style>