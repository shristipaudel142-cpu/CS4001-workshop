public class AIModel {
    private String modelName;
    private double price; // in NPR per 1 Lakh tokens
    private int parameterCount; // in billions
    private String contextWindow; // e.g., "64K tokens"

    // Constructor
    public AIModel(String modelName, double price, int parameterCount, String contextWindow) {
        this.modelName = modelName;
        this.price = price;
        this.parameterCount = parameterCount;
        this.contextWindow = contextWindow;
    }

    // Accessor methods
    public String getModelName() { return modelName; }
    public double getPrice() { return price; }
    public int getParameterCount() { return parameterCount; }
    public String getContextWindow() { return contextWindow; }

    // Display method
    public String display() {
        return "Model: " + modelName + " | Price: NPR " + price +
                " | Parameters: " + parameterCount + "B | Context: " + contextWindow;
    }
}
