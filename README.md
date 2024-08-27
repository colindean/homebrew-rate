:building_construction: :warning:
This is a stub for an idea that may never happen.
Don't take it seriously unless it actually starts working.
:warning:

# homebrew-rate

Be a part of something. Rate Homebrew packages.

## Usage

Rate a package with:

```shell
brew rate [package]
```

Omit the package name, and `brew rate` will pick an installed package at random for you to rate.
If you're not feeling like rating that package, you can safely use Ctrl+C to exit the rating.

Feeling generous?
Run `brew rate --all` and it will ask you to rate everything listed in `brew list --installed-on-request`.
If you're not feeling like rating a package, you can safely use Ctrl+D to skip it or Ctrl+C to exit the rating session.

## Where does the rating data go?

Data is submitted to the :ghost: "Ratings Service for Homebrew" :ghost:
where it will be analyzed and reported in aggregate.

Limiting the impact of bad actors will be an exercise in moderation!

## Inspiration

Memes, like many silly ideas.

![Windows dialog: Rate your experience creating a folder](https://github.com/user-attachments/assets/84c8f1a9-5156-4291-9977-02c38ebd6781)
![CLI: mkdir --rate](https://github.com/user-attachments/assets/fb433b56-3738-4b73-9696-8d9c3c71a576)
