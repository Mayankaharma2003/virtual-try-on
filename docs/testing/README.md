# Testing Guide

## Testing Strategy

### 1. Unit Testing
```typescript
// Component testing
describe('Button Component', () => {
  it('renders correctly', () => {
    render(<Button>Click me</Button>);
    expect(screen.getByText('Click me')).toBeInTheDocument();
  });
});

// Hook testing
describe('useTryOn Hook', () => {
  it('loads clothing data', async () => {
    const { result } = renderHook(() => useTryOn('clothing-id'));
    await waitFor(() => {
      expect(result.current.data).toBeDefined();
    });
  });
});
```

[Previous testing content...]
