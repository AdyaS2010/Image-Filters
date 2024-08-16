# Image Filter Projects

## Description
These projects are image filter tools written in C. They apply various filters to BMP images, such as blur, grayscale, reflection, sepia, and edge detection. The programs read an input BMP file, apply the specified filter, and write the filtered image to an output BMP file.

## Features
- Apply various filters to BMP images:
  - Blur
  - Grayscale
  - Reflection
  - Sepia (first project only)
  - Edge detection (second project only)
- Ensure proper usage and file format validation
- Allocate memory for image processing

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Image-Filters.git
   ```
2. Navigate to the project directory:
   ```bash
   cd filter
   ```
3. Compile the code:
   ```bash
   make filter-less
   make filter-more
   ```

## Usage
### First Version
1. Run the application:
   ```bash
   ./filter-less [flag] infile outfile
   ```
   Replace `[flag]` with one of the following:
   - `b` for blur
   - `g` for grayscale
   - `r` for reflection
   - `s` for sepia

### Second Version
1. Run the application:
   ```bash
   ./filter-more [flag] infile outfile
   ```
   Replace `[flag]` with one of the following:
   - `b` for blur
   - `e` for edge detection
   - `g` for grayscale
   - `r` for reflection

## Example
### First Project Functionality
```bash
$ ./filter-less g input.bmp output.bmp
```

### Second Project
```bash
$ ./filter-more e input.bmp output.bmp
```

## Contributing
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m 'Add some feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

## License
This project is not licensed under any License currently.
