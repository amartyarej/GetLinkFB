Get any link copied from Facebook posts cleaned of tracking and filters

## Setup

1. **Clone the repository:**
```
git clone https://github.com/amartyarej/GetLinkFB.git
cd GetLinkFB/
```
2. **Make the file GetLink executable:**
```
chmod +x GetLink
```
3. **Create a symlink to `~/.local/bin/GetLink`:**
```
ln -s "$(pwd)/GetLink" ~/.local/bin/GetLink
```
(Ensure `~/.local/bin` is in your `$PATH`.)

## Usage
Run the tool with:
```GetLink "<link>"```

### Example Use Cases
- Get a link:
```
GetLink "https://l.facebook.com/l.php?u=https%3A%2F%2Fwww."
```
