# Floating Labels

## Example

```html
<div class="form-floating mb-3">
  <input
    type="email"
    class="form-control"
    id="floatingInput"
    placeholder="name@example.com"
  />
  <label for="floatingInput">Email address</label>
</div>
<div class="form-floating">
  <input
    type="password"
    class="form-control"
    id="floatingPassword"
    placeholder="Password"
  />
  <label for="floatingPassword">Password</label>
</div>
```

```html
<form class="form-floating">
  <input
    type="email"
    class="form-control"
    id="floatingInputValue"
    placeholder="name@example.com"
    value="test@example.com"
  />
  <label for="floatingInputValue">Input with value</label>
</form>
```

```html
<form class="form-floating">
  <input
    type="email"
    class="form-control is-invalid"
    id="floatingInputInvalid"
    placeholder="name@example.com"
    value="test@example.com"
  />
  <label for="floatingInputInvalid">Invalid input</label>
</form>
```

## Textareas

```html
<div class="form-floating">
  <textarea
    class="form-control"
    placeholder="Leave a comment here"
    id="floatingTextarea"
  ></textarea>
  <label for="floatingTextarea">Comments</label>
</div>
```

```html
<div class="form-floating">
  <textarea
    class="form-control"
    placeholder="Leave a comment here"
    id="floatingTextarea2"
    style="height: 100px"
  ></textarea>
  <label for="floatingTextarea2">Comments</label>
</div>
```

## Selects

```html
<div class="form-floating">
  <select
    class="form-select"
    id="floatingSelect"
    aria-label="Floating label select example"
  >
    <option selected>Open this select menu</option>
    <option value="1">One</option>
    <option value="2">Two</option>
    <option value="3">Three</option>
  </select>
  <label for="floatingSelect">Works with selects</label>
</div>
```

## Disabled

```html
<div class="form-floating mb-3">
  <input
    type="email"
    class="form-control"
    id="floatingInputDisabled"
    placeholder="name@example.com"
    disabled
  />
  <label for="floatingInputDisabled">Email address</label>
</div>
<div class="form-floating mb-3">
  <textarea
    class="form-control"
    placeholder="Leave a comment here"
    id="floatingTextareaDisabled"
    disabled
  ></textarea>
  <label for="floatingTextareaDisabled">Comments</label>
</div>
<div class="form-floating mb-3">
  <textarea
    class="form-control"
    placeholder="Leave a comment here"
    id="floatingTextarea2Disabled"
    style="height: 100px"
    disabled
  ></textarea>
  <label for="floatingTextarea2Disabled">Comments</label>
</div>
<div class="form-floating">
  <select
    class="form-select"
    id="floatingSelectDisabled"
    aria-label="Floating label disabled select example"
    disabled
  >
    <option selected>Open this select menu</option>
    <option value="1">One</option>
    <option value="2">Two</option>
    <option value="3">Three</option>
  </select>
  <label for="floatingSelectDisabled">Works with selects</label>
</div>
```

## Readonly plaintext

```html
<div class="form-floating mb-3">
  <input
    type="email"
    readonly
    class="form-control-plaintext"
    id="floatingEmptyPlaintextInput"
    placeholder="name@example.com"
  />
  <label for="floatingEmptyPlaintextInput">Empty input</label>
</div>
<div class="form-floating mb-3">
  <input
    type="email"
    readonly
    class="form-control-plaintext"
    id="floatingPlaintextInput"
    placeholder="name@example.com"
    value="name@example.com"
  />
  <label for="floatingPlaintextInput">Input with value</label>
</div>
```

## Input groups

```html
<div class="input-group mb-3">
  <span class="input-group-text">@</span>
  <div class="form-floating">
    <input
      type="text"
      class="form-control"
      id="floatingInputGroup1"
      placeholder="Username"
    />
    <label for="floatingInputGroup1">Username</label>
  </div>
</div>
```

```html
<div class="input-group has-validation">
  <span class="input-group-text">@</span>
  <div class="form-floating is-invalid">
    <input
      type="text"
      class="form-control is-invalid"
      id="floatingInputGroup2"
      placeholder="Username"
      required
    />
    <label for="floatingInputGroup2">Username</label>
  </div>
  <div class="invalid-feedback">Please choose a username.</div>
</div>
```

## Layout

```html
<div class="row g-2">
  <div class="col-md">
    <div class="form-floating">
      <input
        type="email"
        class="form-control"
        id="floatingInputGrid"
        placeholder="name@example.com"
        value="mdo@example.com"
      />
      <label for="floatingInputGrid">Email address</label>
    </div>
  </div>
  <div class="col-md">
    <div class="form-floating">
      <select class="form-select" id="floatingSelectGrid">
        <option selected>Open this select menu</option>
        <option value="1">One</option>
        <option value="2">Two</option>
        <option value="3">Three</option>
      </select>
      <label for="floatingSelectGrid">Works with selects</label>
    </div>
  </div>
</div>
```
