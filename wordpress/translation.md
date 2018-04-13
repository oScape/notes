# Translation system


## String

- Display :
  ```php
  __( 'Hello, dear user!', 'my-text-domain' );
  ```
- Echo :
  ```php
  _e( 'Hello, dear user!', 'my-text-domain' );
  ```
- Escape :
  ```php
  echo '<h2>' . esc_html__( 'Hello, dear user!', 'my-text-domain' ) . '</h2>';
  ```
- Escape and echo :
  ```php
  esc_html_e( 'Hello, dear user!', 'my-text-domain' );
  ```
