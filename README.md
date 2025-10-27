# SIMCODES-ISU.github.io
Source for the SIMCODES website

## Building Locally

1. Ensure `ruby-bundler` is installed. On Ubuntu this is done by:

   ```.sh
   sudo apt install ruby-dev ruby-bundler
   ```

2. Clone this repo, i.e.,

   ```.sh
   git clone https://github.com/SIMCODES-ISU/SIMCODES-ISU.github.io
   ```

3. Install the dependencies via bundler. This is done by:

   ```.sh
   cd SIMCODES-ISU.github.io/docs
   bundle config set path 'vendor/bundle'
   bundle install
   ```

4. Launch the website server via:

   ```.sh
   bundle exec jekyll serve
   ```

## Adding a new cohort

1. Add a directory to `docs` named `_students-XXXX` (replacing `XXXX` with the
   year).
2. Add an `images` directory to `_students-XXXX`.
3. Have students add their profiles to `_students-XXXX` and images to
   `images`.
4. Add `students-XXXX` to the "Collections" section of `_config.yaml`. Follow
   tha pattern for previous cohorts.
5. Add a new cohort section to `students.md`. Again follow the pattern from
   previous cohorts. 