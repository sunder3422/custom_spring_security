1- This code is of Spring boot security to demonstrate how you can use custom login credentials.
2- Here i have used SQL database
  These queries are needed to insert data in database
  INSERT INTO `users` VALUES
  (1,'john@gmail.com','john','$2a$10$5PiyN0MsG0y886d8xWXtwuLXK0Y7zZwcN5xm82b4oDSVr7yF0O6em','john'),
  (2,'admin@gmail.com','admin','$2a$10$gqHrslMttQWSsDSVRTK1OehkkBiXsJ/a4z2OURU./dizwOQu5Lovu','admin');

  INSERT INTO `roles` VALUES (1,'ROLE_ADMIN'),(2,'ROLE_USER');

  INSERT INTO `users_roles` VALUES (2,1),(1,2);
