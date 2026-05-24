# Python While Loop — Complete Practice Problems (Basic to Pro)
### 170 Problems across 17 Concepts

---

## BASIC

---

### 1. `while` condition (Basic)

1.1. Print numbers from 1 to 10.
1.2. Print numbers from 10 to 1 (countdown).
1.3. Print all even numbers from 2 to 20.
1.4. Print all odd numbers from 1 to 19.
1.5. Print the sum of numbers from 1 to 100.
1.6. Print multiples of 5 from 5 to 50.
7. Print numbers from 1 to 50 that are divisible by both 2 and 3.
8. Keep dividing a number by 2 until it's less than 1. Print each step. (Start with 64)
9. Print the multiplication table of 7 (7x1 to 7x10).
10. A snail climbs 3 meters up a wall each day but slips 1 meter each night. The wall is 10 meters tall. Print how many days it takes to reach the top.

---

### 2. `break`

1. Print numbers from 1 upward, stop when you hit the first multiple of 6.
2. Loop through numbers 1 to 100, stop when the sum exceeds 50. Print the number that caused it.
3. Print numbers from 1 to 20 but stop immediately when you hit a prime number greater than 10.
4. Search for the number 7 in `[3, 1, 4, 1, 5, 7, 9, 2]`. Print its index and break.
5. Print numbers from 100 downward, stop when you hit the first number divisible by 13.
6. Loop from 1 to 1000, break when you find the first number whose digits sum to 10.
7. Simulate a guessing game: the answer is 42. Loop through guesses `[10, 55, 42, 30]` and break when correct.
8. Loop through `["cat", "dog", "error", "bird"]`, break when you encounter `"error"`.
9. Print squares of numbers (1, 4, 9...) and break when the square exceeds 100.
10. Loop through a password list `["abc", "123", "pass", "secret99"]`, break when you find one longer than 7 characters.

---

### 3. `continue`

1. Print numbers 1 to 20, skip multiples of 4.
2. Print numbers 1 to 30, skip numbers that contain the digit 3.
3. Loop through `[1, -2, 3, -4, 5, -6]`, skip negative numbers and print only positives.
4. Print numbers 1 to 50, skip all numbers divisible by both 2 and 5.
5. Loop through `["apple", "", "banana", "", "cherry"]`, skip empty strings and print the rest.
6. Print numbers 1 to 100, skip perfect squares (1, 4, 9, 16...).
7. Loop through a list of ages `[15, 22, 17, 30, 16, 25]`, skip anyone under 18 and print the rest.
8. Print numbers 1 to 20, skip numbers whose reverse is also in the range (e.g., 12 and 21).
9. Loop through `[10, 0, 5, 0, 8]`, skip zeros (to avoid division errors) and print 100 divided by each number.
10. Print numbers 1 to 40, skip numbers that are both odd and greater than 25.

---

### 4. `while/else`

1. Search for `"mango"` in `["apple", "banana", "cherry"]`. Print found or not found using `while/else`.
2. Loop from 1 to 10. If you never encounter a multiple of 11, print `"No multiples of 11 found"` using `else`.
3. Search for a negative number in `[3, 7, 2, 8, 5]`. Use `while/else` to report if none exist.
4. Loop through `[2, 4, 6, 8, 10]` searching for an odd number. Use `else` to confirm all are even.
5. Search for `"admin"` in `["user1", "user2", "user3"]`. Use `while/else` to handle access control messaging.
6. Loop from 1 to 20. Break if you find a number divisible by both 3 and 7. Use `else` if none found.
7. Search for a value greater than 100 in `[10, 50, 30, 80, 20]`. Use `while/else`.
8. Loop through `["jpg", "png", "pdf", "gif"]` looking for `"exe"`. Use `else` to confirm no dangerous files.
9. Search for a palindrome in `["hello", "racecar", "world"]`. Use `while/else`.
10. Loop through numbers 2 to 20 looking for a prime. Break on first prime found, use `else` if none (there won't be — think about why!).

---

### 5. `while True` + user input

1. Keep asking the user to enter a number until they enter 0. Then print "Goodbye!".
2. Build a simple calculator: keep asking for two numbers and an operator (+, -, *, /). Exit when user types "quit".
3. Ask the user to guess a number between 1 and 10. Keep looping until they guess correctly.
4. Keep asking the user for a password until they enter the correct one (`"python123"`). Count failed attempts.
5. Build a simple menu: print options 1, 2, 3, 4 (quit). Keep showing the menu until user picks 4.
6. Keep asking the user to enter a positive number. If they enter a negative, warn them and ask again.
7. Simulate a login system: ask for username and password, allow 3 attempts before locking out.
8. Keep asking the user to enter a word. Build a sentence from all words entered. Stop when they type "done".
9. Keep asking the user for a number and add it to a running total. Stop when they type "stop". Print the total.
10. Ask the user to enter even numbers only. Warn and re-ask if they enter an odd number. Stop after 5 valid inputs.

---

## INTERMEDIATE

---

### 6. Looping through lists with `while`

1. Print all elements of `["red", "green", "blue", "yellow"]` using a while loop.
2. Print all elements of a list in reverse using a while loop.
3. Find the maximum value in `[3, 7, 2, 9, 1, 5]` using a while loop (no `max()`).
4. Find the minimum value in `[10, 4, 7, 1, 8]` using a while loop (no `min()`).
5. Count how many times `"a"` appears in `["a", "b", "a", "c", "a", "d"]` using a while loop.
6. Loop through `[1, 2, 3, 4, 5]` and build a new list with each value doubled.
7. Remove all occurrences of `0` from `[1, 0, 2, 0, 3, 0, 4]` using a while loop.
8. Find the index of `"banana"` in `["apple", "mango", "banana", "grape"]` using a while loop.
9. Flatten `[[1, 2], [3, 4], [5, 6]]` into `[1, 2, 3, 4, 5, 6]` using nested while loops.
10. Rotate a list `[1, 2, 3, 4, 5]` to the left by 2 positions using a while loop.

---

### 7. Nested `while` loops

1. Print a 5x5 grid of stars using nested while loops.
2. Print a multiplication table (1-5 x 1-5) using nested while loops.
3. Print a right-angled triangle of numbers (row 1: "1", row 2: "1 2", etc.) up to 5 rows.
4. Print all pairs (i, j) where i and j are between 1 and 4 and i < j.
5. Find all factor pairs of 36 using nested while loops.
6. Print a hollow square of stars (5x5, only border).
7. Search a 2D list `[[1,2],[3,4],[5,6]]` for the value `4` and print its row and column index.
8. Print Pascal's triangle first 5 rows using nested while loops.
9. Sort a list `[5, 2, 8, 1, 9]` using bubble sort (nested while loops).
10. Print a pyramid pattern of stars (5 rows, centered).

---

### 8. `while` with multiple conditions (`and`/`or`)

1. Loop while `count < 10` AND `total < 50`. Print count and total each iteration (total += count).
2. Keep looping while a number is NOT equal to 5 AND NOT equal to 10. Start at 1.
3. Loop while `x > 0` OR `y > 0`. Decrement both each iteration (x=5, y=3).
4. Loop while username is not `"admin"` AND attempts < 3. Simulate login.
5. Loop while a list is not empty AND the last element is not 0. Pop elements each iteration.
6. Keep a game running while `health > 0` AND `enemies > 0`. Decrease both each round.
7. Loop while `temperature > 0` OR `pressure > 100`. Simulate system monitor.
8. Keep reading input while it's not `"quit"` AND not `"exit"`.
9. Loop while `stock > 0` AND `budget > 0`. Simulate buying items costing 10 each.
10. Loop while `i < 100` AND the number is not a perfect square. Print the first perfect square found.

---

### 9. Flags / sentinel variables

1. Use a `found = False` flag to search for `7` in `[2, 4, 6, 8, 7, 10]`. Print result using the flag.
2. Use a `running = True` flag to control a while loop. Set it to False when count reaches 5.
3. Use a `valid = False` flag to keep asking for input until the user enters a number between 1-10.
4. Use an `error = False` flag. Loop through `[10, 5, 0, 8]`, set flag to True if 0 is found (division risk).
5. Use a `logged_in = False` flag for a login system. Set True on correct credentials.
6. Use a `game_over = False` flag for a number guessing game. Set True when correct guess is made.
7. Use a `duplicate_found = False` flag to check if any duplicates exist in `[1, 2, 3, 2, 4]`.
8. Use a `done = False` sentinel to build a to-do list from user input. Stop when user types "done".
9. Use an `is_prime = True` flag to check if a number is prime using a while loop.
10. Use a `timeout = False` flag and a counter to simulate a retry mechanism (max 3 retries).

---

## ADVANCED

---

### 10. `while` with `try/except` (error handling)

1. Keep asking for a number until the user enters a valid integer (handle `ValueError`).
2. Loop through `[10, 0, 5, 0, 2]` and divide 100 by each. Use try/except to handle `ZeroDivisionError`, continue on error.
3. Keep asking for a filename to open. Use try/except to handle `FileNotFoundError`. Exit when file opens successfully.
4. Loop through `["1", "two", "3", "four", "5"]` and convert to int. Use try/except to skip non-numeric strings.
5. Simulate parsing JSON strings `['{"a":1}', 'bad', '{"b":2}']`. Use try/except to skip invalid JSON.
6. Keep asking user for a date string (YYYY-MM-DD). Use try/except to validate format. Exit on valid date.
7. Loop through a list of URLs and try to fetch each. Use try/except to handle connection errors and continue.
8. Keep asking for an index and print `mylist[index]`. Use try/except for `IndexError`. Exit on valid access.
9. Try to convert user input to float in a loop. Use try/except and keep a count of failed attempts.
10. Loop through operations `["10/2", "5/0", "8/4"]`. Use try/except to safely evaluate each and print results.

---

### 11. Retry patterns

1. Simulate an API call that fails randomly. Retry up to 3 times. Print success or failure.
2. Retry a database connection up to 5 times with a 1-second wait between attempts.
3. Implement exponential backoff: wait 1s, 2s, 4s, 8s between retries (4 max retries).
4. Retry a file write operation up to 3 times. Print which attempt succeeded.
5. Simulate a flaky function that succeeds on the 3rd call. Use a retry loop to call it.
6. Retry with a max attempts counter AND a timeout counter (whichever hits first stops the loop).
7. Build a retry decorator concept: wrap any function call in a while loop with MAX_RETRIES.
8. Retry an HTTP request. On success (status 200) break. On 4xx don't retry. On 5xx retry up to 3 times.
9. Implement retry with jitter: add a small random wait between retries to avoid thundering herd.
10. Build a retry logger: each retry prints attempt number, error type, and wait time before next attempt.

---

### 12. Pagination pattern

1. Simulate paginating a list of 25 items, 5 per page. Print each page using a while loop.
2. Fetch "database records" in batches of 10 from a list of 47 items. Print each batch.
3. Paginate through a list and let the user press Enter to see the next page. Stop at end.
4. Implement offset-based pagination: keep incrementing offset by BATCH_SIZE until no records returned.
5. Paginate a list of blog posts (simulate with a list of 30 strings), 3 per page.
6. Implement cursor-based pagination: use the last item's ID as the next cursor.
7. Build a search paginator: paginate through results and stop early if the target item is found.
8. Paginate API results (simulated with a list), counting total items processed across all pages.
9. Paginate and aggregate: sum values across all pages of `[1..100]` in batches of 10.
10. Paginate in reverse: start from the last page and work backward using while loop.

---

### 13. Polling pattern (wait until something happens)

1. Poll a simulated task status every second. Status changes to "done" after 3 polls. Print each poll.
2. Poll a file for changes (simulate by checking a variable that changes after N iterations).
3. Implement a timeout: poll every 1 second, give up after 10 seconds if condition not met.
4. Poll a queue (simulate with a list). Process items as they appear, stop when queue is empty for 3 consecutive polls.
5. Poll a health check endpoint (simulate). Retry until status is "healthy" or max retries exceeded.
6. Simulate waiting for a payment to clear. Poll every 2 seconds, timeout after 30 seconds.
7. Poll a job queue (list). Process first available job, wait if empty, stop after 5 empty polls.
8. Implement long polling: simulate a server that responds after a delay (use a counter as delay).
9. Poll two conditions simultaneously: stop when BOTH are true (task done AND result saved).
10. Build a progress poller: poll a task and print a progress percentage each poll until 100%.

---

## PRO / PRODUCTION

---

### 14. `while` loops in Django views (conceptual + pseudocode)

1. Write a Django view that retries a database query up to 3 times on `OperationalError`.
2. Write a view that paginates through all published posts and returns them in batches of 10.
3. Write a view that polls a background task status and returns the result once complete.
4. Write a view that keeps trying to acquire a lock on a resource, with timeout.
5. Write a view that processes a queue of pending emails and sends them one by one.
6. Write a view that validates incoming data in a loop, collecting all errors before responding.
7. Write a view that retries an external API call (e.g., payment gateway) up to 3 times.
8. Write a view that streams paginated results to the client as a generator.
9. Write a view that loops through user permissions until it finds the right access level.
10. Write a view that keeps reading from a WebSocket connection until the client disconnects.

---

### 15. Batch processing database records

1. Simulate fetching 1000 user records in batches of 100. Print batch number and record count.
2. Process a batch of orders: mark each as "processed" and move to next batch of 50.
3. Batch delete old records: delete records older than 30 days, in batches of 200.
4. Batch update: loop through all posts in batches of 50, add a "migrated" flag to each.
5. Aggregate in batches: calculate total sales from 500 records, processing 100 at a time.
6. Batch export: write records to a CSV file in chunks of 250 to avoid memory issues.
7. Batch send notifications: send emails to users in batches of 20, with a 1-second pause between batches.
8. Batch validate: loop through 300 records in batches of 30, flag invalid ones for review.
9. Batch import: read a large list of records and insert into a simulated DB in batches of 100.
10. Batch reindex: loop through all search records in batches of 50 and update their search index.

---

### 16. Rate limiting with `while`

1. Simulate rate limiting: allow only 5 requests per second. Use a while loop with a counter and sleep.
2. Implement a token bucket: start with 10 tokens, consume 1 per request, refill 1 per second.
3. Loop through 20 API calls, but pause for 1 second after every 5 calls (rate limit window).
4. Simulate a backoff: if a rate limit error occurs, wait 2x longer each time before retrying.
5. Build a request queue: process requests while under the rate limit, hold when limit is hit.
6. Implement per-user rate limiting: track requests per user, block if they exceed 10/minute.
7. Simulate rate limiting with burst allowance: allow 10 requests immediately, then 1/second after.
8. Build a rate limiter that logs each throttled request with a timestamp.
9. Implement sliding window rate limiting: track requests in a 60-second window using a while loop.
10. Combine rate limiting with retry: if rate limited, wait and retry up to 3 times before giving up.

---

### 17. Background task polling

1. Simulate a Celery-like task: poll every 2 seconds until task status is "SUCCESS" or "FAILURE".
2. Poll a task and implement a progress bar (print % complete each poll).
3. Poll multiple tasks simultaneously (simulate with a list of task objects with statuses).
4. Poll with timeout: give up after 60 seconds if task hasn't completed.
5. Poll and notify: when task completes, simulate sending a notification to the user.
6. Poll a task queue: keep processing tasks while the queue is not empty.
7. Implement dead letter handling: if a task fails after 3 retries, move it to a failed_tasks list.
8. Poll a scheduled task: only start polling after a minimum wait time (simulate with counter).
9. Poll and aggregate results: collect results from 5 parallel tasks (simulated), combine once all done.
10. Build a task monitor: poll all running tasks, print their status table every 5 seconds, stop when all complete.

---