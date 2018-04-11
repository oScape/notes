# Translation system

## String

- Display :
  ```
  __( 'Hello, dear user!', 'my-text-domain' );
  ```
- Echo :
  ```
  _e( 'Hello, dear user!', 'my-text-domain' );
  ```
- Escape html :
  ```
  echo '<h2>' . esc_html__( 'Hello, dear user!', 'my-text-domain' ) . '</h2>';
  ```
- Escape and echo :
  ```
  esc_html_e( 'Hello, dear user!', 'my-text-domain' );
  ```
