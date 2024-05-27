class Recipe {
  final String id;
  final String title;
  final String description;
  final String imageUrl;
  final String ingredients;
  final String steps;

  Recipe({
    required this.id,
    required this.title,
    required this.description,
    required this.imageUrl,
    required this.ingredients,
    required this.steps,
  });

  factory Recipe.fromJson(Map<String, dynamic> json) {
    return Recipe(
      id: json['id'],
      title: json['title'],
      description: json['description'],
      imageUrl: json['imageUrl'],
      ingredients: json['ingredients'],
      steps: json['steps'],
    );
  }
}
