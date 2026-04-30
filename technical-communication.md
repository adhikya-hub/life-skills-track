# Tackling Performance and Scaling Issues

There is an increase in user traffic, and the project is experiencing performance issues such as slow response times and system crashes. This is happening because the current resources are no longer sufficient to handle the growing demand. Now is the time to explore solutions like load balancing and scaling techniques to keep the project running.

## Scaling Techniques

![Scaling Comparison Diagram](https://www.cloudkeeper.com/cms-assets/s3fs-public/inline-images/table-02.png)

Source: https://www.cloudkeeper.com/cms-assets/s3fs-public/inline-images/table-02.png

### Vertical Scaling

Vertical Scaling means increasing the capacity of the existing server by adding more CPU, RAM, or storage. It is easy to implement since no architectural changes are required, but it still has the limitation of a single point of failure.

### Horizontal Scaling

Horizontal Scaling means adding more servers to distribute the load. It solves the problem of a single point of failure, but the setup is complex and harder to maintain.

## Load Balancers

A load balancer is necessary to implement horizontal scaling successfully. It distributes the load evenly across the servers, preventing a single server from being overloaded. Algorithms like Round Robin and Least Connections are used for distribution.

## Conclusion

Vertical scaling is a good short-term solution that can be achieved with minimal code changes, but horizontal scaling with a proper load balancer is a more robust long-term approach.

## References

- https://www.mongodb.com/resources/basics/horizontal-vs-vertical-scaling  
- https://aws.amazon.com/what-is/load-balancing/  
- https://www.digitalocean.com/resources/articles/horizontal-scaling-vs-vertical-scaling
