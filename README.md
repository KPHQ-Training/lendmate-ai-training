# LendMate VA training: entry page

A single static page that sends VAs to the quiz site, where the guide, quizzes and study materials sit behind login.

The guide, PDFs and practice quiz are NOT served from here. They live in the private storage bucket `materials` of the quiz site's Supabase project and open only for signed-in users. See `storage.sql` in the `lendmate-quiz-app` repo.
