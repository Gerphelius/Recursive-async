# Recursive-async

Need to make function startRecursive which: 

1. Fetch 10 users from the array;
1. Call processUser(users[i].id);
1. Process those 10 users in parallel;
1. Wait for those 10 to finish processing;
1. Then sum the result of the promise;
1. Then recursivly run the next 10 users;
1. Until the `users` array is empty;

1. Then finally spit out total collect sum;
1. Response should be "Total: 4950".
