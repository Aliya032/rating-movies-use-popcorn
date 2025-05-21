- This is how elements are passed as props as an alternative to children.

`        <Box element={<MovieList movies={movies} />} />
        <Box
          element={
            <>
              <WatchedSummary watched={watched} />
              <WatchedMovieList watched={watched} />
            </>
          }
        />`

- Default props in React: `export default function StarRating({ maxRating = 5 })`
