# Supabase Setup
Anonymous Sign-Ins must be enabled. Run `database.sql` in the same Supabase project. Confirm `public.srs_vision_state` is in the `supabase_realtime` publication. Deploy all files together. The app uses local-first saving and Supabase cloud sync with Realtime plus a 5-second polling fallback.
